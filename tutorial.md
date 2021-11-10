
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
  html {
  scroll-behavior: smooth;
}
 @import "{{ headmob.github.io }}";

header {
  display: none;
}
body{
  background-color: #131426;
  margin-left:0;
  padding:5%;
  font-family: Arial;
  align:center;
  width:80%;
  }
  a{
  color:#0e94ff;
  text-decoration: none;
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
  h1,h2,h3,h4{
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
<h3>Guide Index</h3>
<p>
 <a href="#freepie">• Download and install OpenTrack or FreePIE</a><br>
 <a href="#firewall">• How to change the settings for Windows Firewall</a><br>
 <a href="#phone">• Phone configuration steps</a><br>
 <a href="#usb">• USB mode</a><br>
 <a href="#ipv4">• Find your local IPV4 address</a><br>
 <a href="#shortcut">• Set up your preferred shortcuts</a><br>
 </p>
 <div style="padding:5%">
<div id="google">
  <h2>Download and Install OpenTrack or FreePIE</h2>
<p>
  → Download OpenTrack here: <a href="https://github.com/opentrack/opentrack/releases">Github Link</a><br>
→ Download FreePIE here: <a href="https://andersmalmgren.github.io/FreePIE/">Github Link</a><br><br>
Install and run the free and open-source OpenTrack or FreePIE application on your computer, then follow these steps:
 </p>
  <h4>OpenTrack</h4>
  <p>
1. Select “UDP over network” as the input. Click the tool icon to the right of this and note the port number (default: 4242) – you will
need this later.<br>
2. As Output, choose "Freetrack 2.0 Enhanced" and "Both" in its settings<br>
3. Your PC setup is almost done!<br>
  </p>
  <p style="color:#fbfbfb;">
This guide is intended for use to get up and running fairly quickly. It is not designed for explaining the intricacies of all the options or
settings that are available. For a complete guide check this link out: Click here<br>
    </p>
</div>
<div id="firwall">
<h3>How to Change the Settings for Windows Firewall</h3>
  <p>
This is the simplest and quickest way to allow UDP inbound on Port 4242<br>
1. Press the Windows key → Type “cmd” and select "Command Prompt"<br>
2. Copy and run this command from Command Line as an Administrator to open the port<br>
  </p>
  <p style="color:#fbfbfb;background-color: #1c1d2e;border-radius: 5px;font-style: italic;width:40%;padding:10px">
netsh advfirewall firewall add rule name="Open UDP Port 4242" dir=in action=allow
    protocol=UDP localport=4242</p>
  <p>
This is the more complicated method<br><br>
1. Press the Windows key → Type “Firewall” , Select “Firewall & network protection”<br>
2. Scroll down and select “Advanced settings”<br>
3. Select “Inbound Rules”<br>
4. In right panel, choose “New Rule” → “Program” and click the “Next” button<br>
5. Choose “This program path” and click the “Browse” button<br>
6. Choose “OpenTrack.exe” from its installation folder which is probably “c:\program files(x86)\opentrack...”<br>
    </p>
</div>
</div>
