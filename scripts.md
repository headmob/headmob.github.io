
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
  <a href="/scripts" class="active">Scripts</a>
  <a href="/tutorial">Tutorial</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<div style="padding-left:16px">
  <h3>Moving mouse with Android</h3>
  <p>
  def update():
    <br>
    #Apply deadband filter to avoid drift    <br>
    #And continousRotation filter to yaw axis to avoid jumps when passing tracker center    <br>
    x = filters.deadband(filters.delta(math.degrees(filters.continousRotation(android[0].yaw))), deadband)    <br>
    y = filters.deadband(filters.delta(math.degrees(android[0].pitch)), deadband)    <br>
    <br>
    mouse.deltaX = x * multiply    <br>
    mouse.deltaY = y * multiply    <br>
    <br>
if starting:    <br>
    deadband = 0.01    <br>
    multiply = 5    <br>
    android[0].update += update    <br>
  </p>
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


