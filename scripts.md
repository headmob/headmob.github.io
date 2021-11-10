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
  color:#0e94ff;
  text-decoration: none;
  }
header {
  display: none;
}
.topnav {
  overflow: hidden;
  background-color: #1c1d2e;
  border-radius: 5px;
}
h4{
   color: #fff;
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
  height: 100%;
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
  <a href="/scripts" class="active">SCRIPT & CONFIG</a>
  <a href="/tutorial">SETUP GUID</a>
  <a href="/faq">FAQ</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.5/typed.min.js"></script>
<div class="container">
  <h1 class="typing"></h1>
</div>
  <h4>Control mouse Android</h4>
  <p style="color:#fff">
  def update():
  <br>
    x = filters.deadband(filters.delta(math.degrees(android[0].googleYaw)), deadband)<br>
    y = filters.deadband(filters.delta(math.degrees(android[0].googlePitch)), deadband) * -1<br>
<br>
    mouse.deltaX = x * 3<br>
    mouse.deltaY = y * 2.1<br>
<br>
if starting:<br>
    deadband = 0.09<br>
    android[0].update += update<br>
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
    strings: ["Sample Script", "Moving mouse by Androird", "Control your pc with face tracking", "Sampel codes"],
    typeSpeed: 100,
    backSpeed: 60,
    loop: true,
  });  
</script>


<div class="footer">
  <p style="float:left;padding:5px;text-align:left;margin-left:30px;">
<b>Support</b><br>
If you have any problem during the usage of HeadMob, don't hesitate<br>
to contact us via headmobtracker@gmail.com
  </p>
  <p style="float:right;padding:5px;text-align:left;margin-right:30px;color:#fcfcfc">
    Made with honey & fire by <b>Pyrobees</b><br>
© 2021 - All rights reserved</p>
</div>

