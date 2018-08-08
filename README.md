# responsive-images

#srcset allows you too tell your browser which image to display depending on screen ratio. Example given below 
<ul>
  
<!--
<img srcset="elva-fairy-320w.jpg 320w,
             elva-fairy-480w.jpg 480w,
             elva-fairy-800w.jpg 800w"
     sizes="(max-width: 320px) 280px,
            (max-width: 480px) 440px,
            800px"
     src="elva-fairy-800w.jpg" alt="Elva dressed as a fairy">
--!>
   

 </ul>



<!doctype html>
<html>
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Simple Theme</title>
<link href="css/multiColumnTemplate.css" rel="stylesheet" type="text/css">
<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
<!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>
<body>
<div class="container">
  <header>
    <div class="primary_header">
      <h1 class="title"> Responsive Images</h1>
    </div>
    <nav class="secondary_header" id="menu">
      <ul>
        <li>ABOUT</li>
        <li>WORK</li>
        <li>PORTFOLIO</li>
        <li>SERVICES</li>
        <li>CLIENTS</li>
        <li>CONTACT</li>
      </ul>
    </nav>
  </header>
  <section>
    <h2 class="noDisplay">Main Content</h2>
    <article class="left_article">
      <h3>How will these responsive tips help me?</h3>
      <p>It is important to learn about this because it allows your users to have a better experience with no your website. If we have images that are not responisive, it could cause your browser to load your pages in minutes not seconds!</p>
      <p>Keep in mind, if you do not have to use an image then dont! It will help your users experience by having faster load. You can also use CSS effects to make your website pop! You can use CSS shadow and gradient effects(We do have to keep in mind that these effects still add on to your loading seconds for your browser.</p>
		<p>CSS also can be implemented for your background. we can use the background size property so our browser adjust the image when increasing pixels size. Do not forget to use your dev tools to learn about download size for your image. </p>
		<ul>
		
			<li>Lets look at the <b>background-size: contain</b></li>
				<ul>
			
						<li>With this the image is sized to that it is as large as possible while still being entirely visible inside its conatainer.</li>
			
			
				</ul>
			<li>Now lets look at <b>background-size: cover</b></li>
				<ul>
			
						<li>This will size the image so that it is as small as possible while still completely filling its container</li>
			
			
			
				</ul>
			<p>Keep in mind that there are many graphical symbols that we can use that are already define in the <b>Unicode character table</b>. This is really nice because there are characters as fonts and they are infinitly scalable!!! You can also add effects on top of that! There are over 110k of these symbols already defined! &#119070;</p>
				<ul>
			
					<li>In order to do this you need to set your unicode character set metatag equal to <b>utf-8</b></li>
			
			
			
				</ul>
			
		
		

		
		</ul>
		<p>
		This is a little Tip incase you did not know. If you want an effect to occure to a class you can use this in your style section. [class*="zocial-"]:before: { THEN THE CSS RIGHT HERE!!!!!} this will cause an effect to all the other classes that start with zocial. These are great! They are vector images that is a huge advantage. 
		
		
		
		
		
		</p>
		<p>It is important to learn different scenerios where you use svg files versus png files. An example, if you are using an image for mutiple pages, it would be smart to use the <i>src</i> tag externally. </p>
    </article>
    <aside class="right_article"><img src="images/placeholder.jpg" alt="" width="400" height="200" class="placeholder"/> </aside>
  </section>
  <div class="row">
    <div class="columns">
      <p class="thumbnail_align"> <img src="images/bkg_06.jpg" alt="" class="thumbnail"/> </p>
      <h4>TITLE</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud.</p>
    </div>
    <div class="columns">
      <p class="thumbnail_align"> <img src="images/bkg_06.jpg" alt="" class="thumbnail"/> </p>
      <h4>TITLE</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud.</p>
    </div>
    <div class="columns">
      <p class="thumbnail_align"> <img src="images/bkg_06.jpg" alt="" class="thumbnail"/> </p>
      <h4>TITLE</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud.</p>
    </div>
    <div class="columns">
      <p class="thumbnail_align"> <img src="images/bkg_06.jpg" alt="" class="thumbnail"/> </p>
      <h4>TITLE</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud.</p>
    </div>
  </div>
  <div class="row blockDisplay">
    <div class="column_half left_half">
      <h2 class="column_title">LEFT COLUMN</h2>
    </div>
    <div class="column_half right_half">
      <h2 class="column_title">RIGHT COLUMN</h2>
    </div>
  </div>
  <div class="social">
    <p class="social_icon"><img src="images/bkg_06.jpg" width="100" alt="" class="thumbnail"/></p>
    <p class="social_icon"><img src="images/bkg_06.jpg" width="100" alt="" class="thumbnail"/></p>
    <p class="social_icon"><img src="images/bkg_06.jpg" width="100" alt="" class="thumbnail"/></p>
    <p class="social_icon"><img src="images/bkg_06.jpg" width="100" alt="" class="thumbnail"/></p>
  </div>
  <footer class="secondary_header footer">
    <div class="copyright">&copy;2015 - <strong>SIMPLE Theme</strong></div>
  </footer>
</div>
</body>
</html>
