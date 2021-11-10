<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
@import "{{ headmob.github.io }}";
body{
  background-color: #131426;
  margin-left:0;
  padding:5%;
  font-family: Arial;
  align:center;
  width:80%
  }
  a{
  color:#0e94ff
  }
header {
  display: none;
}
.topnav {
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

</style>
<div class="topnav" id="myTopnav">
  <a href="/" class="active">HEADMOB</a>
  <a href="/scripts">SCRIPT & CONFIG</a>
  <a href="/tutorial">SETUP GUID</a>
  <a href="/about">FAQ</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
<div style="width:90%">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.5/typed.min.js"></script>
<div class="container">
  <h1 class="typing"></h1>
</div>
  
  <p style="color:#fff">With HeadMob, you have the chance to maximize your immersive gaming experience as it tracks your head movements in all six degrees of freedom and transfer the coordinates with no delay to the game you are playing on your PC.
<br>
• Compatible with any simulation games using OpenTrack or TrackIR<br>
• Adjust the sensitivity and offset of each axis<br>
• No expensive headset, glasses, or extra hardware is required<br>
• Connects over WiFi, no need for annoying cables<br>
• All tracking computations are performed on phone<br>
• Simple one-time setup<br>
<br>
Short list of games compatible with HeadMob<br>
- Microsoft Flight Simulator<br>
- Star Citizens<br>
- IL-2 Great Battles<br>
- War Thunder<br>
- Star Wars: Squadrons<br>
- Arma 2/3<br>
- Rise of Flight<br>
- IL-2 Cliffs of Dover<br>
- Flight Simulator X<br>
- Assetto Corsa<br>
- Euro Truck<br>
- Elite: Dangerous<br>
- Project Cars<br>
And any game that supports FreeTrack or TrackIR protocol</p>

  <a href="http://play.google.com" id="download">Download HeadMob Now</a>


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

