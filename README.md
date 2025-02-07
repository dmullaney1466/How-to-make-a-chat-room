{
 “_id” : ObjectId(“5809171b71e640556be904ef”),
 “name” : “Sudheesh Shetty”,
 “handle” : “sudheesh”,
 “password” : “556624370”,
 “phone” : “8888888888”,
 “email” : “sudheeshshetty@gmail.com”,
 “friends” : [
    {
      “name” : “abc”,
      “status” : “Friend”
    },
    {
      “name” : “xyz”,
      “status” : “Friend”
    }
 ],
 “__v” : 0
}
app.post(‘/register’,function(req,res){})

app.post(‘/login’,function(req,res){})

app.post(‘/friend_request’,function(req,res){})

app.post(‘/friend_request/confirmed’,function(req,res){})
