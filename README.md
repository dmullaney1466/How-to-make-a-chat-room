// unframed 
var blocked = `
    <link href="/css/enbed.css" rel="stylesheet" type="text/css"/>
const hublink = "https://sites.google.com/student.clevelandcountyschools.org/welcome-to-the-chat-room/home

  <style>
  
    body {
      transform: translate(-50%, -50%);
      text-align: center;
      position: absolute;
      top: 50%;
      left: 50%;
if ( window !== window.parent )
{   
    try {
        if (window.parent.location.toString() === 'about:blank'){}
    } catch (err) {
        if ((window.location.host) !== (document.referrer.split('/')[2]) && (!document.referrer.includes('Saturn#0020'))){
            window.location.replace(window.location.protocol + window.location.hostname);
        }
    }
      
    h1 { font-size: 25px;}
    .btn { width: 75%; font-weight: bold; font-size: 13px; margin: 5px;}
  
  </style>
  <h1>This embed was blocked by Unframed</h1> <br>
  <button class="btn btn-secondary" onclick="UnframedRedirect()">Go Back</button>
`
if (window.self != window.top) {
  if (!document.referrer.includes(self.location)) {
    document.querySelector("html").innerHTML = blocked
  }
} 
else if ((window.location.href.includes('tgc-assets')) || (window.location.href.includes('swf'))){
    window.location.replace(document.referrer || (window.location.origin + '/'));
}

function UnframedRedirect() {
  open(self.location)
}
