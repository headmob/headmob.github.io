<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
@import "{{ headmob.github.io }}";
body{
  background-color: #131426;
  margin-left:0;
  font-family: Arial;
  align:center;
  }
  a{
  color:#0e94ff
  }
header {
  display: none;
}
.topnav {
  margin:5%;
  overflow: hidden;
  background-color: #1c1d2e;
  border-radius: 5px;
}

.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: left;
  padding: 5px 16px;
  text-decoration: none;
  font-size: 17px;
  margin:10px;

}

.topnav a:hover {
  background-color: #dde;
  color: black;
}

.topnav a.active {
  background-color: #0e94ff;
  color: white;
  margin:10px;
  padding:5px;
  border-radius: 5px;
}

.topnav .icon {
  display: none;
}
#download{
  background-color: #0e94ff;
  color: white;
  margin:10px;
  padding:10px;
  border-radius: 5px;
  text-decoration: none;
  }
@media screen and (max-width: 800px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
  .typing{
   font-size: small;
  }
}

@media screen and (max-width: 800px) {
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
   .typing{
   font-size: medium;
  }
}
 
  
.container {
  position:relative;

  display: grid;
  place-items: left;
}

.typing{
  display:block;
  color:#fbb03b;
}
.typing::after {
  content: '';
  height: 60%;
  padding: 2px;
  margin-left: 10px;
  background-color: #05ccc2;
  animation: typing 1.2s ease infinite;
}
span.typed-cursor {
  display:none;
}


@keyframes typing {
  0% {
    opacity: 1;
  }

  100% {
    opacity: 0;
  }
}
.footer {
   overflow: hidden;
   left: 0;
   bottom: 0;
   width: 100%;
   background-color: #1c1d2e;
   color: white;
  padding:10px;
}
  
</style>
<div class="topnav" id="myTopnav">
  <a href="/">HEADMOB</a>
  <a href="/scripts">SCRIPT & CONFIG</a>
  <a href="/tutorial">SETUP GUIDE</a>
  <a href="/faq" class="active">FAQ</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
<div style="padding:5%;line-height: 1.6;text-align: justify;text-justify: inter-word;">
  <p>
  <br>
    <br>
    <br>
    <br>
    <br>
    <br>
  This page is under maintenance
     <br>
    <br>
    <br>
    <br>
    <br>
  </p>

<script>
  function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
  
let typed = new Typed(".typing", {
    strings: ["Enjoy flight and driving simulation fames", "Let's make you a part of the game!", "Turn your phone into a head tracker", "No Extra CPU Load on Your PC","It's Time to dive into the Game!"],
    typeSpeed: 100,
    backSpeed: 60,
    loop: true,
  });  
</script>
</div>


<div class="footer">
  <p style="float:left;padding:5px;text-align:left;margin-left:30px;">
<b>Support</b><br>
If you have any problem during the usage of HeadMob, don't hesitate<br>
to contact us via headmobtracker@gmail.com
  </p>
  <p style="float:right;padding:5px;text-align:left;margin-right:30px;color:#fcfcfc">
    Made with honey & fire by <b>Pyrobees</b><br>
?? 2021 - All rights reserved</p>
</div>
