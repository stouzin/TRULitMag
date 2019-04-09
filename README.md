<!DOCTYPE html>
<html>
<head>
   <!--

    
    Home Page TRU LIT Magazine
    Author: Jonathan Bowden Shane Touzin
    Date:   1/28/19

   -->
   
   <meta charset="utf-8" />
   <title>TRU Lit Magazine</title>
   
   
   <link href="side.css" rel="stylesheet">
   <link href="tb_base.css" rel="stylesheet">
   <link href="tb_visual3.css" rel="stylesheet">
   <link href="tb_styles3.css" rel="stylesheet">
   <link href="slideshow.css" rel="stylesheet">
   <link href="header.css" rel="stylesheet">
   
   
</head>

<body>

	<header>
		<img src="bookheader.jpg" alt="Books" />
		<div class="titleText">TRU LITERATURE MAGAZINE</div>
		<nav class="horizontal" id="mainLinks">
        <ul>
			<li><a href="home.html">Home</a></li>
				<li class="dropdown">
					<a href="javascript:void(0)" class="dropbtn">Archive</a>
					<div class="dropdown-content">
						<a href="#">Link 1</a>
						<a href="#">Link 2</a>
						<a href="#">Link 3</a>
					</div>
				</li>
            <li><a href="submit.html">Submit</a></li>
            <li><a href="about.html">About Us</a></li>
        </ul>
		</nav>
    </header>
	
	<main class="grid-container" class="responsive">
      <title class="item1">
         <h1>TRU Lit Magazine</h1>	 
      </title>
	  
      <nav class="scrollingNav">
      <ul>
         <li class ="side"><a href="tss_home.html">Story One</a></li>
         <li class ="side"><a href="https://www.tru.ca/">Story Two</a></li>
         <li class ="side"><a href="tss_bike.html">Story3</a></li>
         <li class ="side" ><a href="tss_swim.html" >Emma Yarrow <br> goes to the Moon</a></li>
		 <li class ="side"><a href="tss_coach.html">Story5</a></li>
         <li class ="side"><a href="http://www.active.com/">Story 6</a></li>        
      </ul>
	  </nav>
		<article class="slideShowImages">
		<div class="slideshow-container">

			<div class="mySlides fade">
  
				<img src="img_nature_wide.jpg" style="width:100%" class="responsive">
					<div class="titleTop">
						<div class="titleText">Story One</div>
					</div>
		
					<div class="authorBot">
						<div class="authorText">By: Anon</div>
					</div>
			</div>

			<div class="mySlides fade"> 
				<a href="http://www.google.com">
				<img src="img_snow_wide.jpg" style="width:100%" class="responsive">
				</a>
					<div class="titleTop">
						<div class="titleText">Story Name</div>
					</div>
					
					<div class="authorBot">
						<div class="authorText">By: Shane Touzin</div>
					</div>
			</div>

			<div class="mySlides fade">  
				<img src="img_mountains_wide.jpg" style="width:100%" class="responsive">
					<div class="titleTop">
						<div class="titleText">Story Three</div>
					</div>
					
					<div class="authorBot">
						<div class="authorText">By: Jon Bowden</div>
					</div>
			</div>

			<div class="mySlides fade">
			  
			  <img src="moon.jpg" style="width:100%" class="responsive">
				<div class="titleTop">
					<div class="titleText emma">Emma Yarrow Goes to Moon</div>
				</div>
				
				<div class="authorBot">
					<div class="authorText">By: Janice Parker</div>
				</div>
			</div>

		</div>



		</article>
	</main>
   <footer>
      <nav class="vertical">
         <ul>
            <li><a href="#">TRU English Department</a></li>
            <li><a href="#">Thompson Rivers University</a></li>
            <li><a href="#">Placeholder</a></li>
            <li><a href="#">PlaceHolder2</a></li>
            <li><a href="#">Placeholder3</a></li>
         </ul>
      </nav>
      <nav class="vertical">
         <ul>
            <li><a href="#">Other things</a></li>
            <li><a href="#">Placeholder</a></li>
            <li><a href="#">Research Sites</a></li>
            <li><a href="#">Interest Groups</a></li>
            <li><a href="#">Government Sites</a></li>
         </ul>
      </nav>
      <nav class="vertical">
         <ul>
            <li><a href="#">About TRU Lit Mag</a></li>
            <li><a href="#">Developers</a></li>
            <li><a href="#">Privacy</a></li>
            <li><a href="#">Terms</a></li>
            <li><a href="#">Help</a></li>
         </ul>
      </nav>
      <section></section>
   </footer>
   
<script>
var slideIndex = 0;
var x;


showSlides();



function showSlides() {
	  var i;
	  
	  var slides = document.getElementsByClassName("mySlides");
	  var sides = document.getElementsByClassName("side");
	 
	  
	  for (i = 0; i < slides.length; i++) {
		slides[i].style.display = "none";  
	  }
	  slideIndex++;
	  if (slideIndex > slides.length) {slideIndex = 1}
	  for (i = 0; i < sides.length; i++) {
    sides[i].className = sides[i].className.replace(" active", "");
  }

	
	  
	  slides[slideIndex-1].style.display = "block";  
	  sides[slideIndex-1].className += " active";
	  
	  
	 
	  x = setTimeout(showSlides, 4000); // Change image every 4 seconds
	 
	
	  
	  
}

function mouseOver() {

	
	setTimeout(x, 50000000);
	}
	
function mouseOut() {

	document.getElementsByClassName("mySlides").showSlides() = start;
}
	
	


</script>
</body>
</html>
