<!DOCTYPE html>
<html>
<title>Swiss Beauty</title> 
<!-- comment -->

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<body id="myPage">

<!-- Sidebar on click -->
<nav class="w3-sidebar w3-bar-block w3-white w3-card w3-animate-left w3-xxlarge" style="display:none;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-display-topright w3-text-teal">Close
    <i class="fa fa-remove"></i>
  </a>
  <a href="#" class="w3-bar-item w3-button">Link 1</a>
  <a href="#" class="w3-bar-item w3-button">Link 2</a>
  <a href="#" class="w3-bar-item w3-button">Link 3</a>
  <a href="#" class="w3-bar-item w3-button">Link 4</a>
  <a href="#" class="w3-bar-item w3-button">Link 5</a>
</nav>

<!-- Navbar -->
<div class="w3-top">
 <div class="w3-bar w3-theme-d2 w3-left-align">
  <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-hover-white w3-theme-d2" href="javascript:void(0);" onclick="openNav()"><i class="fa fa-bars"></i></a>
  <a href="#" class="w3-bar-item w3-button "><img src="images/logo2.jpg" style="width: 65px;"></a>
  <a href="#bestseller" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Best sellers</a>
  <a href="#launches" class="w3-bar-item w3-button w3-hide-small w3-hover-white">New Launches</a>
  <a href="#products" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Products</a>
  <a href="#partners" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Our Partners</a>
  <a href="#contact" class="w3-bar-item w3-button w3-hide-small w3-hover-white">Contact</a>
  <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-teal" title="Search"><i class="fa fa-search"></i></a>
 </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-theme-d2 w3-hide w3-hide-large w3-hide-medium">
    <a href="#bestseller" class="w3-bar-item w3-button">Best Seller</a>
    <a href="#launches" class="w3-bar-item w3-button">New Launches</a>
    <a href="#products" class="w3-bar-item w3-button">Products</a>
    <a href="#partners" class="w3-bar-item w3-button">Our Partners</a>
    <a href="#contact" class="w3-bar-item w3-button">Contact</a>
    <!-- <a href="#" class="w3-bar-item w3-button">Search</a> -->
  </div>
</div>

<!-- Image Header -->
<div class="w3-display-container ">
  <img src="images/homepage.jpg" alt="homepage" style="width:100%;min-height:350px;max-height:600px;">

</div>


<!-- best seller Container -->
<div class="w3-container w3-padding-64 w3-center" id="bestseller">
<h2>OUR BEST SELLERS</h2>


<div class="w3-row"><br>

<div class="w3-quarter">
  <img src="images/mini-eyespalette.jpeg" alt="Eyeshadow" style="width:54%" class=" w3-hover-opacity">
  <h3>Ultimate Shadow Pallete</h3>
  <p>&#8377; 199</p>
</div>

<div class="w3-quarter">
  <img src="images/big_blush.webp" alt="blush" style="width:55%" class=" w3-hover-opacity">
  <h3>Ultra Blush Pallete</h3>
  <p>&#8377;349</p>
</div>

<div class="w3-quarter">
  <img src="images/liquid_lipstick.jpg" alt="lipstick" style="width:60%" class=" w3-hover-opacity">
  <h3>Ultra Matte Lipstick </h3>
  <p>&#8377;199</p>
</div>

<div class="w3-quarter">
  <img src="images/liquid_eyeshadow.jpg" alt="eyeshadow" style="width:60.5%" class=" w3-hover-opacity">
  <h3>Metallic Liquid Eyeshadow</h3>
  <p>&#8377;149</p>
</div>

</div>
</div>

<!-- new  launches section-->
<div class="w3-row-padding w3-padding-64 " id="launches" style="background-color:rosybrown;">

<div class="w3-quarter">
<h2 style="color: white;"> NEW LAUNCHES</h2>
<p> <h4>We have launche are all new......</h4><b> Drop & Glow liquid highlighter</b> gives you a very natural glow finish with it's superfine glitter particles. <br><br>
    Be ready to blink and shine your eye like never before with our new<b> Loose Shine foil pigments.</b><br><br>
    Dark circles and Uneven skintone ??? Forget problems like these by using our new <b> High Coverage liquid concealer.</b> for you 
</p>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="images/liquid_highlighter.jpg" alt="Snow" style="width:100%">
  <div class="w3-container">
  <h3> Drop & Glow</h3>
  <h4>Liquid Highlighter</h4>
  <p>&#8377;299</p>
  </div>
  </div>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="images/foil_pigment.jpg" alt="Lights" style="width:100%">
  <div class="w3-container">
  <h3>Loose Shine</h3>
  <h4>Foil Pigment  </h4>
  <p>&#8377;149</p>
  </div>
  </div>
</div>

<div class="w3-quarter">
<div class="w3-card w3-white">
  <img src="images/concealer.jpg" alt="Mountains" style="width:100%">
  <div class="w3-container">
  <h3>High Coverage</h3>
  <h4>Liquid Concealer</h4>
  <p>&#8377;219</p>
  </div>
  </div>
</div>

</div>


  <!-- Product grid -->
  <div class="w3-row w3-center " id="products"> <br><br><br>
    <h2>OUR PRODUCTS</h2><br>
    <div class="w3-col l3 s6">
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/kajal4.jpg" style="width:100%">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>Intense Gel Kajal<br><b>&#8377;199</b></p>
      </div>

      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/liner.jpg" style="width:100%">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>        
        <p>HD Stroke Pen Eyeliner<br><b>&#8377;259</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/tropic_eye.jpg" style="width:100%">
          <span class="w3-tag w3-display-topleft">New</span>
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>The Tropics Eyeshoadow<br><b>&#8377;699</b></p>
      </div>
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/4_blush.jpg" style="width:100%">
        <div class="w3-display-middle w3-display-hover">
          <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
        </div>
        </div>        
        <p>UltraGlow Highlighter Pallete<br><b>&#8377;549</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/foundation1.jpg" style="width:100%">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>Smooth & Flawless Primer+Foundation<br><b>&#8377;449</b></p>
      </div>
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/gel.jpg" style="width:100%">
          <span class="w3-tag w3-display-topleft">Sale</span>
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>Jelly Eyeshadow<br><b class="w3-text-red">&#8377;199</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/eye_long.jpg" style="width:100%">
          <span class="w3-tag w3-display-topleft">Sale</span>
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>Multicolor Baked Pallete<br><b class="w3-text-red">&#8377;549</b></p>
      </div>
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="images/eye_big.jpg" style="width:100%">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>       
        <p>HD Professional Eyeshadow Pallete<br><b>&#8377;1299</b></p>
      </div>
    </div>
  </div>

<!-- service partners section -->
<div class="w3-container w3-padding-64 w3-center " id="partners" style="background-color:#FFDBE9;">
  <h2>OUR SERVICE PARTNERS</h2>

  <div class="w3-row"><br>  
  <div class="w3-quarter">
    <img src="images/nykaa.jpg" alt="Eyeshadow" style="width:50%" class="w3-circle w3-hover-opacity">
    <h3>NYKAA </h3>  
  </div>
  
  <div class="w3-quarter">
    <img src="images/flipkart.png" alt="blush" style="width:50%" class="w3-circle w3-hover-opacity">
    <h3>FLIPKART</h3>    
  </div>
  
  <div class="w3-quarter">
    <img src="images/amazon.png" alt="lipstick" style="width:50%" class="w3-circle w3-hover-opacity">
    <h3>AMAZON </h3>   
  </div>
  
  <div class="w3-quarter">
    <img src="images/myntra.jpg" alt="eyeshadow" style="width:50%" class="w3-circle w3-hover-opacity">
    <h3>MYNTRA</h3>   
  </div>
  
  </div>
  </div>

<!-- Footer -->
<footer class="w3-container w3-padding-15 w3-theme-d1 w3-center" id="contact">
  <h4>Follow Us</h4>
  <a class="w3-button w3-large w3-pink" href="javascript:void(0)" title="Facebook"><i class="fa fa-facebook"></i></a>
  <a class="w3-button w3-large w3-pink" href="javascript:void(0)" title="Twitter"><i class="fa fa-twitter"></i></a>
  <!-- <a class="w3-button w3-large w3-teal" href="javascript:void(0)" title="Google +"><i class="fa fa-google-plus"></i></a> -->
  <a class="w3-button w3-large w3-pink" href="javascript:void(0)" title="Google +"><i class="fa fa-instagram"></i></a>
  <a class="w3-button w3-large w3-pink " href="javascript:void(0)" title="youtube"><i class="fa fa-youtube"></i></a>
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">Swiss Beauty India </a></p>

  <div style="position:relative;bottom:100px;z-index:1;" class="w3-tooltip w3-right">
    <span class="w3-text w3-padding w3-pink w3-hide-small">Go To Top</span>   
    <a class="w3-button w3-theme" href="#myPage"><span class="w3-xlarge">
    <i class="fa fa-chevron-circle-up"></i></span></a>
  </div>
</footer>

<script>
// Script for side navigation
function w3_open() {
  var x = document.getElementById("mySidebar");
  x.style.width = "300px";
  x.style.paddingTop = "10%";
  x.style.display = "block";
}

// Close side navigation
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}

// Used to toggle the menu on smaller screens when clicking on the menu button
function openNav() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}



function currentDiv(n) {
  showDivs(slideIndex = n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" w3-opacity-off", "");
  }
  x[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " w3-opacity-off";
}

</script>

</body>
</html>
