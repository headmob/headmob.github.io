
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
@import "{{ headmob.github.io }}";

header {
  display: none;
}
.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #dde;
  color: black;
}

.topnav a.active {
  background-color: #edbb2f;
  color: white;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}
</style>
<h2>Headmob Tracker</h2>
<div class="topnav" id="myTopnav">
  <a href="/">Home</a>
  <a href="/script">Scripts</a>
  <a href="/tutorial" class="active">Tutorial</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<div style="padding-left:16px">
 
  - Press the Windows key :
 - Type ‘Firewall' , Select ‘Firewall & network protection’ :
 
- Scroll down and select ‘Advanced settings’:
 - From left select ‘Inbound Rules’ :
 
- In right panel, choose ‘New Rule’ :
 - Choose ‘Program’ and click Next:
 
- Choose ‘This program path’ and click Browse :
 - Choose ‘opentrack.exe’ from folder that you installed probably “c:\program files(x86)\opentrack\opentrack.exe”
 ------------------------------------

- Right click on your network symbol at the bottom right of Windows, choose ‘Open Network & Internet Setting’ :
 - Choose ‘Properties’ :
 
- Choose ‘Private’ instead of ‘Public’ (This will make your PC discoverable to your mobile devices) :
 
- Press windows key and type ‘Command prompt’ :
 - Type ‘ipconfig’ and Enter :
 
- Find your local Ipv4 address (normally starts with 192.168... but might 10.0... or something else) :
 - Now restart ‘opentrack’ :
 
</div>

<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>


