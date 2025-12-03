# the-real-me[periods code (1).txt](https://github.com/user-attachments/files/23900437/periods.code.1.txt)

<!doctype html>
<html>
<head>
<p><a href="file:///C:/Users/SKCN/Desktop/website/form.html"><input type="button" value="Register" /></a>
<style>
h1 {text-align:center;}
h1{font-size:300%;}
p{font-size:160%;}
<br>
* {box-sizing: border-box}
</style>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
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
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>

<body bgcolor="#FAAFBA">  (pink)
<h1> THE REAL ME </h1>
<hr>
<br>
<p style="color:blue;"><b><i>What is a Period?</i></b></p>
<p> Periods or Menstruation is a natural biological process in which blood and tissue from your uterus come out from your vagina. 
This usually happens once in a month. The  onset of menstrual periods in girls is the body's way of preparing itself for possible pregnancy.
The ovaries are responsible for release of <b>hormones, oestrogen, and progesterone</b>.
These female hormones signal the building up of the uterine lining or endometrium that nurtures a fertilised egg.</p> 
<p>The same hormones signal the release of an egg from one of the ovaries during ovulation. 
This egg travels through the <b>Fallopian Tube</b> and attaches to the uterine lining - ready for fertilization. 
In the absence of a sperm cell to fertilize the egg, the uterine lining breaks down and is shed by way of a period.</p>
<p>This lining takes on an average of around 28 days to build up, break down, and eventually get shed. 
Most women experience a period cycle of anywhere between <b>21 to 35 days.</b></p>
<br>
<br>
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="C:\Users\SKCN\Desktop\website\fumss9ug_benefits-of-menstrual-cup-_625x300_09_February_22.jpg" style="width:100%">
  <div class="text">Caption One</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="C:\Users\SKCN\Desktop\website\img1.jpg" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="C:\Users\SKCN\Desktop\website\period-abnormalities-to-not-ignore.jpg" style="width:100%">
  <div class="text">Caption Three</div>
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>
<script>
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>
</script>
<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
<br>
<p><a href="file:///C:/Users/SKCN/Desktop/website/infopage.html">For more information...</a>
</body>
</html>








page 2 register page

<html>
<head>
<title>
Registration Page
</title>
</head>
<body bgcolor="lightskyblue">
<h1> Register</h1>
<form>


<lable>First Name </lable>
<input type="text" name="firstname" size="15"/><br><br>
<lable> Last Name </lable>
<input type="text" name="lastname" size="15"/><br><br>


<lable>Gender</lable><br>
<input type="radio" name="male"/>Male<br>
<input type="radio" name="female"/>Female<br>
<input type="radio" name="male"/>Other
<br>
<br>


<lable>Phone: </lable>
<input type="text" name="country code" value="+91" size="2"/>
<input type="text" name="phone" size="10"/> <br><br>
Your Personal Opinion
<br>
<textarea cols="80" rows="5" value="Your Personal Opinion">
</textarea>
<br><br>
Email:
<input type="email" id="email" name="email"/><br>
<br><br>
Password:
<input type="Password" id="pass" name="pass"> <br>
<br><br>
Re-type Password:
<input type="Password" id="repass" name="repass"><br><br>
<input type="button" value="Submit"/>
</form>
</body>
</html>



page 3 more info

<!doctype html>
<html>
<head>
<style>
h1 {text-align:center;}
h1 {font-size:300%;}
p{font-size:160%;}
<br>
</style>
</head>
<body bgcolor="#FAAFBA">
<h1>MY BLEEDING MY CHOICE</H1>
<hr><br>
<p style="color:blue;"><b><I>Do Periods hurt ?</I></b></p>
<p><h4>Many women experiences premenstrual syndrome or PMS during the weeks leading up to their period.
This may be characterised by symptoms such as mood swings, acne, anxiety, feeling irritable or short tempered.</h4></p>
<P><h4> You are also likely to experience period pain during the first couple of days of your period. 
It can range between substantial cramps in your lower abdomen or dull stomach pain during periods accompanied by an aching lower back.</h4></p>
<p> <h4>While pain during the period is normal, if cramps during period become unberable and start to interfere with day-to-day life, 
it is better to pay your doctor a visit for a through examination of underlying cause.
<p style="color:blue;"><b><i>How to reduce period pain ?</i></b></p>
<p><h3>Period pain generally eases away as your period progresses but if period cramps are keeping you from going about your day as usual,  
you can try following remedies:</h3></P>
<ul>
<li> A hot water bag or a heated pain relief pad can make periods significantly less painful</li>
<li> Take over-the counter pain medication.</li>
</ul>
<p> <h4>However, if taking pain medications does not help with menstrual cramps, it is advisable to pay your doctor a visit.</h4></p>
<p style="color:blue;"><b><i>What are the signs that I am approaching my periods ?</i></b></p>
<p><h4>If your periods haven't started then, periods generally start about two years after your breasts begin to develop.
But there are that can signal the arrival of your first period. 
Right around the same time, you will also notice the growth of hair in your pubic area and a mucus like vaginaal discharge which can be clear, 
white, or even slightly cloudy yellowish in color. 
These are both signs that will help you better understant the relationship between puberty and the onset of your periods.</h4></P>
<p><h4> If you have started menstruating, then some signs of approaching periods that tend to stay across the course of life are:</h4></p>
<ul>
<li>You may see signs of Pre-Menstrual Syndrome</li>
<li>You may feel bloated and gassy</li>
<li>You may experiences acne</li>
<li>You may experiences abdominal cramps</li>
<li>You may have a headache</li>
<li> You may feel mood swings</li>
<li>You may feel body pain</li>
<li> You may face hyperacidity</li>
</ul>
<p><h4> Observing these period symptoms is very important since they can help you to be prepared with period management 
products such as sanitary pads and tampons. </p></h4>
</body>
</html>







