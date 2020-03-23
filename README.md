
<html>
<head>
<meta name="author" content="lukas">
<meta name="editor" content="html-editor phase 5">
<body text="#000000" bgcolor="#FFFFFF" link="#FF0000" alink="#FF0000" vlink="#FF0000">
<h2>Herzlich Willkommen im Greuter G&auml;stewlan</h2>
 <p>Bitte <b>downloaden</b> Sie keine <b>gro&szlig;en</b> <b>Dateien</b>. Dies k&ouml;nnte die <b>Qualit&auml;t</b> des Internets <b> massiv beeintr&auml;chtigen </b> und somit andere WLAN-Nutzer bei ihrer Arbeit st&ouml;ren. Nun wollen wir keine weitere Zeit von Ihnen in Anspruch nehmen.</p>
<p>Wir danken herzlich f&uuml;r Ihr Verst&auml;dnis. Bei Problemen und Fragen sind wir gerne f&uuml;r Sie da!</p>
<p>Viel Spa&szlig; im Internet w&uuml;nscht die Familie Greuter.
<b>Ihr Ger&auml;t wurde erfolgreich im WLAN-Netz angemeldet</b>
 <hr>
 <p>Alle <b>Infos</b> zum <b>Coronavirus (Covid-19)</b> gibts 
<a href="https://www.sozialministerium.at/Informationen-zum-Coronavirus/Neuartiges-Coronavirus-(2019-nCov).html">hier</a>
 <form method="get" action="http://goggle.at" target="_blank">
         <input type="submit" value="Googel neuer Tab"> 
</form>
<form method="get" action="http://goggle.at"> 
         <input type="submit" value="Goggle gleiches Fenster">
<a href="http://google.at">
           <button> Hier können Sie eine Googlesuche starten</button>
</a>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>

<h2>Automatic Slideshow</h2>
<p>Change image every 2 seconds:</p>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="img_snow_wide.jpg" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="img_mountains_wide.jpg" style="width:100%">
  <div class="text">Caption Three</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

</body>
</html> 

