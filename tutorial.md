
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
  p{
  color:#fff;
  }
  h1,h2{
  color:#fff;
  }
</style>
<div class="topnav" id="myTopnav">
  <a href="/">HEADMOB</a>
  <a href="/scripts">SCRIPT & CONFIG</a>
  <a href="/tutorial" class="active">SETUP GUID</a>
  <a href="/about">FAQ</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>



