@@ -1,7 +1,12 @@
import strutils, asyncdispatch, sets, hashes
import karax/[karaxdsl, vdom], jester, ws, ws/jester_extra, json
import std/[strutils, asyncdispatch, sets, hashes, json]
import karax/[karaxdsl, vdom], jester, ws, ws/jester_extra

converter toString(x: VNode): string = $x
type User = object
  name: string
  socket: WebSocket
proc hash(x: User): Hash = hash(x.name)
var chatrooms = initTable[string, HashSet[User]]()
template index*(rest: untyped): untyped =
  buildHtml(html(lang = "en")):
    head:
@@ -13,18 +18,12 @@ template index*(rest: untyped): untyped =
      nav(class="container-fluid"):
        ul: li: a(href = "/", class="secondary"): strong: text "Simple Chat"
      main(class="container"): rest
type User = object
  username: string
  socket: WebSocket
proc hash(x: User): Hash = hash(x.username)
proc chatInput(): VNode = buildHtml(input(name="message", id="clearinput", autofocus="", required=""))
proc sendAll(users: HashSet[User], msg: string) =
  for user in users: discard user.socket.send(msg)
template buildMessage*(msg: untyped): untyped =
  buildHtml(p(id="content", hx-swap-oob="beforeend")):
    msg
    br()
var chatrooms = initTable[string, HashSet[User]]()
  buildHtml(tdiv(id="content", hx-swap-oob="beforeend")):
    tdiv: msg
routes:
  get "/":
    let html = index:
@@ -35,36 +34,36 @@ routes:
          input(type="text", name="room")
        label:
          text "Username"
          input(type="text", name="username")
          input(type="text", name="name")
        input(type="submit", value="Join")
    resp html
  get "/chat":
    let html = index:
      h1: text @"room"
      tdiv(hx-ws="connect:/chat/" & @"room" & "/" & @"username"):
      tdiv(hx-ws="connect:/chat/" & @"room" & "/" & @"name"):
        p(id="content")
        form(hx-ws="send", id="message"): chatInput()
    resp html
  get "/chat/@room/@username":
  get "/chat/@room/@name":
    var ws = await newWebSocket(request)
    var user = User(username: @"username", socket: ws)
    var user = User(name: @"name", socket: ws)
    try:
      chatrooms.mgetOrPut(@"room", initHashSet[User]()).incl(user)
      let joined = buildMessage:
        italic: text user.username
        italic: text user.name
        italic: text " has joined the room"
      chatrooms[@"room"].sendAll(joined)
      while user.socket.readyState == Open:
        let sentMessage = (await user.socket.receiveStrPacket()).parseJson["message"]
        discard user.socket.send(chatInput())
        let reply = buildMessage:
          bold: text user.username
          bold: text user.name
          text ": " & sentMessage.getStr()
        discard user.socket.send(chatInput())
        chatrooms[@"room"].sendAll(reply)
    except:
      chatrooms[@"room"].excl(user)
      let left = buildMessage:
        italic: text user.username
        italic: text user.name
        italic: text " has left the room"
      chatrooms[@"room"].sendAll(left)
    resp "" # need this so jester doesn't throw a fit
    resp ""
