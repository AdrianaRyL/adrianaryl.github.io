<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
.bgimg {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url('/w3images/profile_girl.jpg');
  min-height: 100%;
}
</style>
</head>
<body>
<!-- Sidebar with image -->
<nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width:40%">
  <div class="bgimg"></div>
</nav>

<!-- Hidden Sidebar (reveals when clicked on menu icon)-->
<nav class="w3-sidebar w3-black w3-animate-right w3-xxlarge" style="display:none;padding-top:150px;right:0;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="closeNav()" class="w3-button w3-black w3-xxxlarge w3-display-topright" style="padding:0 12px;">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Home</a>
    <a href="#papers" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Papers</a>
    <a href="#about" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">About</a>
    <a href="#teaching" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Teaching</a>
    <a href="#contact" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Contact</a>
  </div>
</nav>

<!-- Page Content -->
<div class="w3-main w3-padding-large" style="margin-left:40%">

  <!-- Menu icon to open sidebar -->
  <span class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black" style="width:auto;right:0;" onclick="openNav()"><i class="fa fa-bars"></i></span>

  <!-- Header -->
  <header class="w3-container w3-center" style="padding:128px 16px" id="home">
    <h1 class="w3-jumbo"><b>Adriana Reyna</b></h1>
    <p>Complex Networks Researcher.</p>
    <img src="/w3images/profile_girl.jpg" class="w3-image w3-hide-large w3-hide-small w3-round" style="display:block;width:60%;margin:auto;">
    <img src="/w3images/profile_girl.jpg" class="w3-image w3-hide-large w3-hide-medium w3-round" width="1000" height="1333">
    <button class="w3-button w3-light-grey w3-padding-large w3-margin-top">
      <i class="fa fa-download"></i> Download Resume
    </button>
  </header>

  <!-- Portfolio Section -->
  <div class="w3-padding-32 w3-content" id="papers">
    <h2 class="w3-text-grey">Papers</h2>
    <hr class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="/w3images/wedding.jpg" style="width:100%">
        <img src="/w3images/rocks.jpg" style="width:100%">
        <img src="/w3images/sailboat.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="/w3images/underwater.jpg" style="width:100%">
        <img src="/w3images/chef.jpg" style="width:100%">
        <img src="/w3images/wedding.jpg" style="width:100%">
        <img src="/w3images/p6.jpg" style="width:100%">
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-32" id="about">
    <h2>About</h2>
    <hr class="w3-opacity">
    <p>Some text about me. Some text about me. I am lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing
      elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </p>
    <h3 class="w3-padding-16">Research interests</h3>
    <p class="w3-wide">Complex Networks</p>
    <div class="w3-light-grey">
    </div>
    <p class="w3-wide">Nonlinear Dynamics</p>
    <div class="w3-light-grey">
    </div>
    <p class="w3-wide">Diffusion Processes</p>
    <div class="w3-light-grey">
    </div>
    <p class="w3-wide">Resources Distribution</p>
    <div class="w3-light-grey">
    </div><br>


    
    <!-- Grid for Teaching -->
    <div class="w3-content w3-justify w3-text-grey w3-padding-32" id="teaching">
    <h3 class="w3-padding-16">Teaching</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
    <!-- End Teaching tables -->
    </div>
    </div><br>  
    

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Download Resume
    </button>

    <!-- Network -->
    <h3 class="w3-padding-24">Network</h3>
    <img src="/w3images/avatar_smoke.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">Prof. Jesús Gómez Gardeñes. </span> Universidad de Zaragoza.</p>
    <p>PHD supervisor & friend</p><br>
   
    <img src="/w3images/bandmember.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">Prof. Alex Arenas. </span> Universitat Rovira i Virgili.</p>
    <p>Collaborator & friend.</p><br>
    
    <img src="/w3images/avatar_g2.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">David Soriano Paños.</span> Universitat Rovira i Virgili.</p>
    <p>Collaborator & friend.</p><br>
    
    
  <!-- End About Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-32 w3-content w3-text-grey" id="contact" style="margin-bottom:64px">
    <h2>Contact </h2>
    <hr class="w3-opacity">

    <div class="w3-section">
      <p></i> Institutional e-mail address: adriana [dot] ryl [at ] gmail [dot] com </p>
      <p></i> Permanent e-mail address: a [dot] reyna [at ] tec [dot] mx </p>
    </div>
    
  <!-- End Contact Section -->
  </div>  
  
  <!-- Footer -->
  <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin:-24px">
    <!--i class="fa fa-instagram w3-hover-opacity"></i-->
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <!--i class="fa fa-linkedin w3-hover-opacity"></i-->
    <p class="w3-medium">© Adriana Reyna. <a target="_blank" class="w3-hover-text-green"> All rights reserved. </a></p>
  <!-- End footer -->
  </footer>
  
<!-- END PAGE CONTENT -->
</div>

<script>
// Open and close sidebar
function openNav() {
  document.getElementById("mySidebar").style.width = "60%";
  document.getElementById("mySidebar").style.display = "block";
}

function closeNav() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>
</body>
</html>
