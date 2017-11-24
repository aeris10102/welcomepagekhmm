<!DOCTYPE html>
<html>
<head>
    
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>Homepage</title>

	<link href="css/style.css" rel="stylesheet">
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet">
    <link rel='shortcut icon' type='image/x-icon' href='favicon.ico' />
    
	<link href='https://fonts.googleapis.com/css?family=Noto+Sans' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=Righteous' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=PT+Sans' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=Hammersmith+One' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=NTR' rel='stylesheet' type='text/css'>

    
<style>
    html,
body {
    height: 100%;
}

body {
	overflow-x: hidden;
}

#scrollUp {
  bottom: 20px;
  right: 20px;
  width: 38px; /* Width of image */
  height: 38px; /* Height of image */
  background: url(../images/top.png) no-repeat;
}


/******** Slider ********/

.carousel, .item, .active {
    height: 100%;
}

.carousel-inner {
    height: 100%;
}

.fill {
    width: 100%;
    height: 100%;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    background-size: cover;
    -o-background-size: cover;
}


#mainCarousel .slider_overlay {
    background: none repeat scroll 0 0 #252333;
    height: 100%;
    opacity: 0.8;
    position: absolute;
    right: 0;
    top: 0;
    width: 100%;
    z-index: 0;
}

#mainCarousel .hero {
    position: relative;
    top: 50%;
    left: 50%;
    z-index: 1000;
    color: #fff;
    text-align: center;
    padding: 0 13%;
    font-family: 'NTR', sans-serif;
    text-shadow: 1px 1px 0 rgba(0, 0, 0, .75);
    -webkit-transform: translate3d(-50%, -50%, 0);
    -moz-transform: translate3d(-50%, -50%, 0);
    -ms-transform: translate3d(-50%, -50%, 0);
    -o-transform: translate3d(-50%, -50%, 0);
    transform: translate3d(-50%, -50%, 0);
}

#mainCarousel .hero h1 {
    font-size: 80px;
    margin: 0;
    padding: 0;
    font-family: 'Hammersmith One', sans-serif;
    text-transform: uppercase;
}

#mainCarousel .hero h3 {
    font-size: 26px;
    margin: 0;
    padding: 0;
}

#mainCarousel .hero button {
	margin-top: 30px;
	background: #42a5f6;
	font-size: 20px;
	padding: 10px 20px;
	outline: none;
}

#mainCarousel .carousel-indicators {
	position: absolute;
	z-index: 1000;
}

#mainCarousel .carousel-control {
	position: absolute;
	z-index: 1000;
}

#mainCarousel .carousel-control.left {
	background-image: none;
}

#mainCarousel .carousel-control.right {
	background-image: none;
}

@media screen and (min-width: 768px) {
#mainCarousel .carousel-control .icon-next, #mainCarousel .carousel-control .icon-prev {
    width: 200px;
    height: 200px;
    margin-top: -100px;
    font-size: 200px;
    margin-right: -100px;
    margin-left: -100px;
    color: #42a5f6;
}
}

#mainCarousel .carousel-indicators .active {
    background: #42a5f6;
    border: 1px solid #0781E6; 
}


/******** Media Queries ********/

@media screen and (max-width: 1071px) {
#mainCarousel .hero h1 {
	font-size: 70px;
}
}

@media screen and (max-width: 938px) {
#mainCarousel .hero h1 {
	font-size: 60px;
}
}

@media screen and (max-width: 799px) {
#mainCarousel .hero h1 {
	font-size: 60px;
}
}

@media screen and (max-width: 799px) {
#mainCarousel .hero h3 {
	font-size: 22px;
}
}

@media screen and (max-width: 608px) {
#mainCarousel .hero h1 {
	font-size: 50px;
}
}

@media screen and (max-width: 608px) {
#mainCarousel .hero h3 {
	font-size: 20px;
}
}

@media screen and (max-width: 507px) {
#mainCarousel .hero h1 {
	font-size: 45px;
}
}

@media screen and (max-width: 507px) {
#mainCarousel .hero h3 {
	font-size: 18px;
}
}

@media screen and (max-width: 400px) {
#mainCarousel .hero h1 {
	font-size: 40px;
}
}

@media screen and (max-width: 400px) {
#mainCarousel .hero h3 {
	font-size: 16px;
}
}

/******** About Section ********/

#about {
	padding-top: 40px;
	padding-bottom: 40px;
}

#about .text h2 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Noto Sans', sans-serif;
	letter-spacing: 1px;
	font-weight: 600;
	text-align: center;
}

#about .text p {
	text-align: center;
	font-family: 'PT Sans', sans-serif;
	font-size: 16px;
}

#about .panel-group {
	margin-top: 30px;
}

#about .panel-heading:hover {
    cursor:pointer;
}

#about .panel-heading {
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;    
}

#about .side-tab:hover {
     cursor: pointer;
}
    
#about .panel.panel-default {
     border: none;
     box-shadow: none !important;
     border-bottom-right-radius: 0px;
     border-bottom-left-radius: 0px;
        
}

#about .panel-heading {
     border: none;
     background-color: #2469A2;
     color: #fff;
}

#about .panel-title {
    font-weight: 400;
    font-size: 18px;
    text-transform: uppercase;
    font-family: 'Noto Sans', sans-serif;
}
 
#about .panel-body {
	border-right: 1px solid #2469A2;
	border-left: 1px solid #2469A2;
	font-family: 'PT Sans', sans-serif;
}     

#about #carousel {
	margin-top: 30px;
	position: relative;
	display: block;
}

#about #carousel .item img {
	width: 100%;
}


/******** Portfolio Section ********/


#portfolio {
	padding-top: 40px;
	padding-bottom: 40px;
	background: #55687C;
}

#portfolio h2 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Noto Sans', sans-serif;
	letter-spacing: 1px;
	font-weight: 600;
	color: #fff;
	border-bottom: 8px solid #42a5f6;
    display: inline-block;
    margin-bottom: 30px;
    padding-bottom: 15px;
    padding-right: 75px;
    line-height: 40px;
}

#portfolio p {
	font-family: 'PT Sans', sans-serif;
	font-size: 17px;
	color: #fff;
}

#portfolio .Portfolio-nav {
	padding:0;
	margin:60px 0 45px 0;
	list-style:none;
	text-align:center;
}

#portfolio .Portfolio-nav li {
	margin:0 10px;
	display:inline;
}

#portfolio .Portfolio-nav li a {
	display:inline-block;
	padding:10px 22px;
	font-size:12px;
	line-height:20px;
	color:#222222;
	border-radius:4px;
	text-transform:uppercase;
	font-family: 'Montserrat', sans-serif;
	background:#f7f7f7;
	margin-bottom:5px;
	transition:all 0.3s ease-in-out;
	-moz-transition:all 0.3s ease-in-out;
	-webkit-transition:all 0.3s ease-in-out;
}

#portfolio .Portfolio-nav li a:hover {
	background:#42a5f6;
	color:#fff;
	text-decoration:none;
}

#portfolio .portfolioContainer{
	margin:0 auto;
	padding-left:15px;
}

#portfolio .portfolioContainer{
	max-width: 1140px;
	min-width: 280px;
}

#portfolio .Portfolio-box {
	text-align:center;
	margin-bottom:30px;
	height:225px;
	width:350px;
	overflow:hidden;
	float:left;
	padding:0;
}

#portfolio .Portfolio-box img{
	margin-bottom:25px;
	transition:all 0.3s ease-in-out;
	-moz-transition:all 0.3s ease-in-out;
	-webkit-transition:all 0.3s ease-in-out;	
}

#portfolio .Portfolio-box img:hover {
	opacity: 0.6;
}

#portfolio .Portfolio-nav li a.current{
	background: #42a5f6;
	color:#fff;
	text-decoration:none;
}
img {
   max-width:100%;
}

/* no transition on .isotope container */

.isotope .isotope-item {
  /* change duration value to whatever you like */
  -webkit-transition-duration: 0.6s;
     -moz-transition-duration: 0.6s;
          transition-duration: 0.6s;
}

.isotope .isotope-item {
  -webkit-transition-property: -webkit-transform, opacity;
     -moz-transition-property:    -moz-transform, opacity;
          transition-property:         transform, opacity;
}


/******** Blog Section ********/


#blog {
	padding-top: 40px;
	padding-bottom: 40px;
	background: #f9f9f9;
}

#blog h2 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Noto Sans', sans-serif;
	letter-spacing: 1px;
	font-weight: 600;
	text-align: center;
}

#blog h2 span {
	color: #42a5f6;
}

#blog .carousel .carousel-inner ul {
	list-style: none;
	padding: 0;
}

#blog .carousel .carousel-inner .thumbnail {
	border: none;
	padding: 0px;
}

#blog .carousel .carousel-inner .thumbnail img {
	width: 100%;
	height: 100%;
	margin-top: 20px;
}

#blog .carousel .carousel-inner .caption h4 {
	font-size: 18px;
	text-transform: uppercase;
}

#blog .carousel .carousel-inner .caption .btn {
	padding: 0px;
	font-size: 16px;
}

#blog .pager li a {
	background: #42a5f6;
	color: #fff;
}


/******** Contact Section ********/


#contact {
	padding-top: 40px;
	padding-bottom: 40px;
}

#contact h2 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Noto Sans', sans-serif;
	letter-spacing: 1px;
	font-weight: 600;
	color: #000;
	border-bottom: 8px solid #42a5f6;
    display: inline-block;
    margin-bottom: 30px;
    padding-bottom: 15px;
    padding-right: 75px;
    line-height: 40px;
}

#contact p {
	font-family: 'PT Sans', sans-serif;
	font-size: 17px;
	color: #000;
}

#contact .contact-form input {
	width: 100%;
	height: 40px;
	margin-top: 25px;
	outline: none;
	padding: 20px;
	font-size: 14px;
	border: 1px solid #000;
}

::-webkit-input-placeholder {
   color: #000;
}


#contact .contact-form textarea {
	width: 100%;
	height: 150px;
	margin-top: 25px;
	outline: none;
	resize: none;
	padding: 20px;
	font-size: 14px;
	border: 1px solid #000;
}

#contact .contact-form button {
	margin-top: 20px;
	padding: 10px 20px;
	background: #42a5f6;
	border: none;
	color: #fff;
	font-size: 16px;
	text-transform: uppercase;
	outline: none;
	transition: background-color 0.5s ease;
}

#contact .contact-form button:hover {
	background: #55687C;
}

#contact .image {
	margin-top: 25px;
}

#contact .image img {
	width: 100%;
	height: 100%;
}


/******** Subscribe Section ********/


#subscribe {
	padding-top: 40px;
	padding-bottom: 40px;
}

#subscribe h2 {
	font-size: 28px;
	text-transform: uppercase;
	font-family: 'Noto Sans', sans-serif;
	letter-spacing: 1px;
	font-weight: 600;
	color: #000;
	border-bottom: 8px solid #42a5f6;
    display: inline-block;
    margin-bottom: 30px;
    padding-bottom: 15px;
    padding-right: 75px;
    line-height: 40px;
}

#subscribe p {
	font-family: 'PT Sans', sans-serif;
	font-size: 17px;
	color: #000;
}

#subscribe .input-group {
    width: 100%;
    margin-top: 30px;
}

#subscribe input.btn.btn-lg,
input.btn.btn-lg:focus {
    outline: none;
    width: 60%;
    height: 60px;
    border-top-right-radius: 0;
    border-bottom-right-radius: 0;
    border: 1px solid #42a5f6;
    text-align: left;
    font-size: 16px;
    cursor: auto;
}

#subscribe button.btn {
    width: 40%;
    height: 60px;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    background: #42a5f6;
    outline: none;
    text-transform: uppercase;
}


/******** Footer ********/


.footer {
	margin-top: 20px;
  	width: 100%;
  	height: 60px;
  	background-color: #1a223d;
  	text-align: center;
}

.footer .text-muted {
	padding: 20px;
	margin: 0px;
	color: #fff;
}

</style>
    
    $[head]
</head>
    
    <body>

    <!-- Navigation -->
    <nav class="navbar navbar-default navbar-fixed-top" role="navigation">
        <div class="container">
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">Free <span>Designz</span></a>
            </div>
            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="#mainCarousel">Home</a>
                    </li>
                    <li>
                        <a href="#about">About</a>
                    </li>
                    <li>
                        <a href="#portfolio">Portfolio</a>
                    </li>
                    <li>
                        <a href="#blog">Blog</a>
                    </li>
                    <li>
                        <a href="#contact">Contact Us</a>
                    </li>
                </ul>
            </div>
            <!-- /.navbar-collapse -->
        </div>
        <!-- /.container -->
    </nav>

    <!-- Full Page Image Background Carousel Header -->
    <header id="mainCarousel" class="carousel slide">
        <!-- Indicators -->
        <ol class="carousel-indicators">
            <li data-target="#mainCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#mainCarousel" data-slide-to="1"></li>
            <li data-target="#mainCarousel" data-slide-to="2"></li>
        </ol>

        <!-- Wrapper for Slides -->
        <div class="carousel-inner">
            <div class="item active">
            <div class="slider_overlay"></div>
                <!-- Set the first background image using inline CSS below. -->
                <div class="fill" style="background-image:url('images/slide1.jpg');">
                    <div class="hero">
                        <hgroup>
                            <h1>Hi, welcome to this template</h1>
                            <h3>Get started below to create a great business</h3>
                        </hgroup>
                        <button class="btn btn-hero btn-lg" role="button">See all features</button>
                    </div>
                </div>
            </div>
            <div class="item">

            <div class="slider_overlay"></div>
                <!-- Set the second background image using inline CSS below. -->
                <div class="fill" style="background-image:url('images/slide2.jpg');">
                    <div class="hero">
                        <hgroup>
                            <h1>Eam et vivendum probatus</h1>
                            <h3>Noster cetero ei mei, cu dicta falli malorum usu</h3>
                        </hgroup>
                    </div>
                </div>
            </div>
            <div class="item">    
            <div class="slider_overlay"></div>
                <!-- Set the third background image using inline CSS below. -->
                <div class="fill" style="background-image:url('images/slide3.jpg');">
                    <div class="hero">
                        <hgroup>
                            <h1>Per ei prima ridens oblique</h1>
                            <h3>Lorem ipsum dolor sit amet, summo populo menandri</h3>
                        </hgroup>
                    </div>
                </div>
            </div>
        </div>

        <!-- Controls -->
        <a class="left carousel-control" href="#mainCarousel" data-slide="prev">
            <span class="icon-prev"></span>
        </a>
        <a class="right carousel-control" href="#mainCarousel" data-slide="next">
            <span class="icon-next"></span>
        </a>

    </header>
    
    <div id="about">
    	<div class="container">
    		<div class="text">
    			<h2>About Us</h2>
    			<hr>
    			<p>Ne aeterno tincidunt nam. Te utamur laboramus necessitatibus quo, nam ea ludus perpetua. Eum et vidit nostro commodo, conceptam dissentiunt definitiones eu eum, putant scripserit cu qui. Rebum nominavi deterruisset in per, id odio case repudiare mea, ius periculis philosophia cu. Mei dolor discere constituam ea, no unum erant nihil qui. In regione dissentias cum.</p>
			</div>

        <div class="col-md-6">
            <!-- begin panel group -->
            <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
                
                <!-- panel 1 -->
                <div class="panel panel-default">
                    <!--wrap panel heading in span to trigger image change as well as collapse -->
                    <span class="side-tab" data-target="#tab1" data-toggle="tab" role="tab" aria-expanded="false">
                        <div class="panel-heading" role="tab" id="headingOne"data-toggle="collapse" data-parent="#accordion" href="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                            <h4 class="panel-title">Responsive Design</h4>
                        </div>
                    </span>
                    
                    <div id="collapseOne" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
                        <div class="panel-body">
                        <!-- Tab content goes here -->
                        <p>Lorem ipsum dolor sit amet, ne sit consul numquam. Quidam causae mel cu, atqui expetendis vis in. Novum erant repudiandae ad ius, et timeam graecis est. In integre tincidunt pro, suas iracundia no nec. An debet nemore eirmod vim, erant vitae recteque usu ex.</p>
                        <p>Sonet fuisset ad vis, ut voluptua verterem volutpat vix, at quaeque invenire pro. Ius eu brute verear lobortis, utroque postulant democritum nam et. At ius modo legendos, ut illum propriae apeirian his. Eu sit idque dignissim. Et nec utamur argumentum, malorum pericula eos te.</p>
                        </div>
                    </div>
                </div> 
                <!-- / panel 1 -->
                
                <!-- panel 2 -->
                <div class="panel panel-default">
                    <!--wrap panel heading in span to trigger image change as well as collapse -->
                    <span class="side-tab" data-target="#tab2" data-toggle="tab" role="tab" aria-expanded="false">
                        <div class="panel-heading" role="tab" id="headingTwo" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                            <h4 class="panel-title collapsed">Efficient Code</h4>
                        </div>
                    </span>

                    <div id="collapseTwo" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
                        <div class="panel-body">
                        <!-- Tab content goes here -->
                        <p>Lorem ipsum dolor sit amet, ne sit consul numquam. Quidam causae mel cu, atqui expetendis vis in. Novum erant repudiandae ad ius, et timeam graecis est. In integre tincidunt pro, suas iracundia no nec. An debet nemore eirmod vim, erant vitae recteque usu ex.</p>
                        <p>Sonet fuisset ad vis, ut voluptua verterem volutpat vix, at quaeque invenire pro. Ius eu brute verear lobortis, utroque postulant democritum nam et. At ius modo legendos, ut illum propriae apeirian his. Eu sit idque dignissim. Et nec utamur argumentum, malorum pericula eos te.</p>
                        </div>
                    </div>
                </div>
                <!-- / panel 2 -->
                
                <!--  panel 3 -->
                <div class="panel panel-default">
                    <!--wrap panel heading in span to trigger image change as well as collapse -->
                    <span class="side-tab" data-target="#tab3" data-toggle="tab" role="tab" aria-expanded="false">
                        <div class="panel-heading" role="tab" id="headingThree"  class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                            <h4 class="panel-title">24 Hour Support</h4>
                        </div>
                    </span>

                        <div id="collapseThree" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
                          <div class="panel-body">
                          <!-- tab content goes here -->
                        <p>Lorem ipsum dolor sit amet, ne sit consul numquam. Quidam causae mel cu, atqui expetendis vis in. Novum erant repudiandae ad ius, et timeam graecis est. In integre tincidunt pro, suas iracundia no nec. An debet nemore eirmod vim, erant vitae recteque usu ex.</p>
                        <p>Sonet fuisset ad vis, ut voluptua verterem volutpat vix, at quaeque invenire pro. Ius eu brute verear lobortis, utroque postulant democritum nam et. At ius modo legendos, ut illum propriae apeirian his. Eu sit idque dignissim. Et nec utamur argumentum, malorum pericula eos te.</p>
                          </div>
                        </div>
                      </div>
            	</div>
             </div> 
             
   	 		 <div class="col-md-6">
    			<div id="carousel" class="carousel slide" data-ride="carousel">
				<!-- Indicators -->
					<ol class="carousel-indicators">
			  			<li data-target="#carousel" data-slide-to="0" class="active"></li>
			    		<li data-target="#carousel" data-slide-to="1"></li>
			    		<li data-target="#carousel" data-slide-to="2"></li>
			    		<li data-target="#carousel" data-slide-to="3"></li>
			    		<li data-target="#carousel" data-slide-to="4"></li>
					</ol>
					<!-- Wrapper for slides -->
					<div class="carousel-inner">
			    		<div class="item active">
			    			<img src="images/placeholder.png" alt="First slide">
			    		</div>
			    		<div class="item">
			    			<img src="images/placeholder.png" alt="Second slide">
			    		</div>
			    		<div class="item">
			    			<img src="images/placeholder.png" alt="Third slide">
			    		</div>
			    		<div class="item">
			    			<img src="images/placeholder.png" alt="Third slide">
			    		</div>
			    		<div class="item">
			    			<img src="images/placeholder.png" alt="Third slide">
			    		</div>
					</div>
				</div>
			</div>
             
        </div>
    </div>
    
    
    <div id="portfolio">
    	<div class="container">
    		<h2>Our Portfolio</h2>
    		<p>Lorem ipsum dolor sit amet, suscipit percipit mea te, est te alia utinam electram. Sea ex doctus numquam, lucilius efficiantur vim id, meis timeam cu usu. Ius atomorum neglegentur ei, ullum accusamus persecuti pro ut. Cu per adipisci quaerendum, an offendit verterem sea. Ut autem apeirian sea, libris eripuit veritus ex ius, legere iriure utamur te ius.</p>
      			<div class="portfolioFilter">  
        			<ul class="Portfolio-nav wow fadeIn delay-02s">
        				<li><a href="#" data-filter="*" class="current" >All</a></li>
            			<li><a href="#" data-filter=".webdesign" >Web design</a></li>
            			<li><a href="#" data-filter=".appdevelopment" >App Development</a></li>
            			<li><a href="#" data-filter=".graphicdesign" >Graphic Design</a></li>
        			</ul>
       			</div> 
    	</div>
    	
       		<div class="portfolioContainer">
            	<div class=" Portfolio-box appdevelopment">
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
                <div class="Portfolio-box webdesign">
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
                <div class=" Portfolio-box appdevelopment">
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
                <div class=" Portfolio-box webdesign" >
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
                <div class=" Portfolio-box graphicdesign">
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
                <div class=" Portfolio-box graphicdesign">
                	<a href="#"><img src="images/placeholder2.png" alt=""></a>	
                </div>
    		</div>
    	
    </div>
    
    
    <div id="blog">
    	<div class="container">
    		<h2>Latest <span>Blog</span> Posts</h2>
    		<hr>
    		<div class="carousel slide" id="myCarousel">
        		<div class="carousel-inner">
           			<div class="item active">
            		 	<ul class="thumbnails">
                        	<li class="col-sm-4">
    							<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                           	 	</div>
                        	</li>
                        	<li class="col-sm-4">
								<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                            	</div>
                        	</li>
                        	<li class="col-sm-4">
								<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                            	</div>
                        	</li>
                    	</ul>
             		</div><!-- /Slide1 --> 
            		<div class="item">
                    	<ul class="thumbnails">
                       		<li class="col-sm-4">
								<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                            	</div>
                        	</li>
                        	<li class="col-sm-4">
								<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                            	</div>
                        	</li>
                        	<li class="col-sm-4">
								<div class="fff">
									<div class="thumbnail">
										<a href="#"><img src="http://placehold.it/360x240" alt=""></a>
									</div>
									<div class="caption">
										<h4>Sed dico menandri</h4>
										<p>Vim ad novum solet, sit id cetero latine pertinax. Pri soleat vocent suscipiantur id, cu qui postea civibus assentior, te natum scripta fastidii mei. Et sea meliore fuisset assueverit.</p>
										<a class="btn btn-mini" href="#">Read More <i class="fa fa-angle-double-right" aria-hidden="true"></i></a>
									</div>
                            	</div>
                        	</li>
                    	</ul>
            		</div><!-- /Slide2 --> 
        		</div>
        
       
	   		<nav>
				<ul class="control-box pager">
					<li><a data-slide="prev" href="#myCarousel" class=""><i class="fa fa-chevron-left" aria-hidden="true"></i></a></li>
					<li><a data-slide="next" href="#myCarousel" class=""><i class="fa fa-chevron-right" aria-hidden="true"></i></a></li>
				</ul>
			</nav>
	   		<!-- /.control-box -->   
                              
   	 		</div><!-- /#myCarousel -->
    	</div>
    </div>
    
    
    <div id="contact">
    	<div class="container">
    		<h2>Contact Us</h2>  
    		<p>Lorem ipsum dolor sit amet, ad harum populo reformidans ius, ei vix verear timeam. Has nibh abhorreant at, ex atqui voluptatum eam. Mei an corpora hendrerit, quo eu legere labitur ornatus.</p>
    		<div class="col-md-6">
    			<div class="contact-form">
					<form action="#" method="post">
						<input id="name" name="name" type="text" placeholder="Name:" required>
						<input id="email" name="email" type="text" placeholder="Email:" required>
						<input id="subject" name="subject" type="subject" placeholder="Subject:" required>
						<textarea id="message" name="message" placeholder="Your Message:" rows="5" required></textarea>
						<br>
						<button name="submit" id="submit" type="submit">Send Message</button>
					</form>
				</div>  
			</div>	
			<div class="col-md-6">
				<div class="image">
					<img src="http://inhabitat.com/wp-content/blogs.dir/1/files/2015/10/The-R%C3%B6nesans-Mecidiyek%C3%B6y-Office-by-Muum-1.jpg" class="img-responsive">
				</div>
			</div>
    	</div>
    	
		<iframe width="100%;" height="300" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" style="pointer-events: none; margin-top: 30px;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2483.281992959266!2d-0.1302576842043993!3d51.5080423184772!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487604ce3941eb1f%3A0x1a5342fdf089c627!2sTrafalgar+Square!5e0!3m2!1sen!2suk!4v1462913556349"></iframe>
		
    </div>
    
    
    <div id="subscribe">
    	<div class="container">
    	    <h2>Subscribe To Us</h2>
    	    <p>Ex per oblique corpora concludaturque, consulatu incorrupte an eum. In his offendit scribentur, eam ne autem tractatos. Affert molestie phaedrum vel ad, dicit audire expetendis qui ut, ne minim deleniti eum. </p>
			<div class="col-md-8 col-md-offset-2">
             	<form action="#">
              		<div class="input-group">
                 		<input class="btn btn-lg" name="email" id="email" type="email" placeholder="Enter your email address" required>
                 		<button class="btn btn-info btn-lg" type="submit">Submit</button>
             		 </div>
            	</form>
			</div>  
    	</div>
    </div>
    
	<div class="footer">
  		<div class="container">
   			<p class="text-muted">All Rights Reserved <a href="http://freedesignz.com">Free Designz</a></p>
  		</div>
	</div>



    <!-- jQuery -->
    <script src="js/jquery.js"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="js/bootstrap.min.js"></script>
    
    <script src="js/jquery.isotope.js"></script>
    
    <script src="js/jquery.scrollUp.min.js"></script>
    
    
	<script type="text/javascript">
	
	$('a[href^="#"]').on('click', function(event) {
    	var target = $(this.getAttribute('href'));
    	if( target.length ) {
       		event.preventDefault();
        	$('html, body').stop().animate({
            	scrollTop: target.offset().top
        	}, 1000);
    	}
	});

	</script>
    
    
    <!-- Navbar Change on Scroll -->
	<script type="text/javascript">
		$(function(){
 		var shrinkHeader = 100;
  		$(window).scroll(function() {
    		var scroll = getCurrentScroll();
      		if ( scroll >= shrinkHeader ) {
           		$('.navbar-default').addClass('shrink');
        	}
       		else {
            	$('.navbar-default').removeClass('shrink');
        	}
  		});
		function getCurrentScroll() {
    		return window.pageYOffset || document.documentElement.scrollTop;
    	}
	});

	</script>    


	<!-- Portfolio Isotope Settings -->
	<script type="text/javascript">

	$(window).load(function(){
  
  
 	 var $container = $('.portfolioContainer'),
     	$body = $('body'),
     	colW = 375,
      	columns = null;

  
  	$container.isotope({
    // disable window resizing
    	resizable: true,
   	 	masonry: {
        columnWidth: colW
    	}
  	});
  
  	$(window).smartresize(function(){
    // check if columns has changed
    	var currentColumns = Math.floor( ( $body.width() -30 ) / colW );
    	if ( currentColumns !== columns ) {
      	// set new column count
      	columns = currentColumns;
      	// apply width to container manually, then trigger relayout
      	$container.width( columns * colW )
        	.isotope('reLayout');
    	}
    
  	}).smartresize(); // trigger resize to set container width
  	$('.portfolioFilter a').click(function(){
        	$('.portfolioFilter .current').removeClass('current');
        	$(this).addClass('current');
 
        	var selector = $(this).attr('data-filter');
        	$container.isotope({
			
            filter: selector,
         });
        	 return false;
   	 	});
  
	});

	</script>
	
	
	<!-- Scroll To Top Settings -->
    <script type="text/javascript">
    
    $(function () {
  		$.scrollUp({
    		scrollName: 'scrollUp', // Element ID
    		topDistance: '300', // Distance from top before showing element (px)
    		topSpeed: 600, // Speed back to top (ms)
    		animation: 'fade', // Fade, slide, none
    		animationInSpeed: 200, // Animation in speed (ms)
    		animationOutSpeed: 200, // Animation out speed (ms)
    		activeOverlay: false, // Set CSS color to display scrollUp active point, e.g '#00FFFF'
    		scrollImg: true,
  		});
	});
    
    </script>
$[header]
	
</body>
$[footer]
</html>

