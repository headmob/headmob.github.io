
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
@import "{{ headmob.github.io }}";
body{
  background-color: #131426;
  margin-left:0;
  padding:0;
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
  text-align: center;
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
</style>
<div class="topnav" id="myTopnav">
  <a href="/" class="active">HEADMOB</a>
  <a href="/scripts">SCRIPT & CONFIG</a>
  <a href="/tutorial">SETUP GUID</a>
  <a href="#about">FAQ</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<div style="padding-left:16px">
  <h1 style="color:#fbb03b">Feel the Way a Real Pilot Feels</h1>
  <p style="color:#fff">With HeadMob, you have the chance to maximize your immersive gaming experience as it tracks your head movements in all six degrees of freedom and transfer the coordinates with no delay to the game you are playing on your PC.

• Compatible with any simulation games using OpenTrack or TrackIR
• Adjust the sensitivity and offset of each axis
• No expensive headset, glasses, or extra hardware is required
• Connects over WiFi, no need for annoying cables
• All tracking computations are performed on phone
• Simple one-time setup

Short list of games compatible with HeadMob
- Microsoft Flight Simulator
- Star Citizens
- IL-2 Great Battles
- War Thunder
- Star Wars: Squadrons
- Arma 2/3
- Rise of Flight
- IL-2 Cliffs of Dover
- Flight Simulator X
- Assetto Corsa
- Euro Truck
- Elite: Dangerous
- Project Cars
And any game that supports FreeTrack or TrackIR protocol</p>
  <a href="http://play.google.com" id="download">Download HeadMob <img src="img/play.png" style="width:20px;height:20px;text-align:center;background: transparent;"/></a>
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


