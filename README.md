# CrossfitOshawa
My first GitHub

<html>
<head>
	<title>Crossfit Oshawa</title>
	<link rel="stylesheet" href="CSS/styles.css">
</head>

<body>
    <script src="jquery.js"></script>
    <script>
			$(document).ready(function() {
		    $(".jumper").on("click", function( e ) {

		        e.preventDefault();

		        $("body, html").animate({ 
		            scrollTop: $( $(this).attr('href') ).offset().top 
		        }, 600);

		    });
		});

			</script>


	<header>
		<nav class="clearfix">
			<ul class="header">
				<li class="logo">
					<img src="https://profilepicsbucket.crossfit.com/47f0f-A329_2-184.jpg" alt="Crossfit Oshawa">
				</li>
			</ul>
			<ul class="section-nav">
				<a class="jumper" href="#Coaches">
					<li>
						Coaches
					</li>
				</a>
				<a class="jumper" href="#Crossfit">
					<li>
						Crossfit
					</li>
				</a>
				<a class="jumper" href="#WOD">
					<li>
						WOD
					</li>
				</a>
				<a class="jumper" href="#Community">
					<li>
						Community
					</li>
				</a>
				<a class="jumper" href="#Pricing">
					<li>
						Pricing
					</li>
				</a>
				<a class="jumper" href="#Location">
					<li>
						Location
					</li>
				</a>
				<a class="jumper" href="#Started">
					<li>
						Visit Us
					</li>
				</a>
			</ul>
		</nav>
	</header>

	<section class="welcome">
		<h1>Welcome to Crossfit Oshawa</h1>
			<p>If you're looking to seriously improve your fitness level, improve on your weaknesses and join a supportive fitness community, you've come to the right place.</p>
			<p>At Crossfit Oshawa, we're not just going to teach you how to become 'fit' we're going to work with you to build a healthy, balanced lifestyle. </p>

		<iframe width="420" height="250" src="https://www.youtube.com/embed/QRLfItnpG9I" frameborder="0" allowfullscreen></iframe>
			
	</section>

	<div id="Coaches"></div>
		<section class="coaches">
			<h1>Meet Cam & Kevin</h1>
				<p>They will be your coach, your trainer and your biggest supporter from day one. </p>
<!-- 					<img src="kev.jpg" alt="Kevin" id="coaches">
 -->		</section>

	<div id="Crossfit"></div>
		<section class="crossfit">
			<h1>So What Exactly is Crossfit?</h1>
				<p>Crossfit is a type of competitive fitness that is usually done in a group setting with measurable results. It incorporates elements from high-intensity interval training, Olympic weightlifting, plyometrics, powerlifting, gymnastics, girevoy sport, calisthenics, strongman and other exercises.</p>
				<br>
				<p> It sounds a lot more intimidating than it really is. All of our workouts are easily scaled to match your age, fitness level or accomodate an injury.</p>
		</section>

	<div id="WOD"></div>
		<section class="workout">
			<h1>Workout of the Day</h1>
				<p>You are given a new workout every day. Sometimes they are short, fast and only involve bodyweight movements. Sometimes they are long, slow and require fairly heavy weights.</p>
				<p>What makes Crossfit great is that you, as an athlete, never know what workout you're up against each day. Your body is constantly challenged and forced to adapt. </p>
		</section>

	<div id="Community"></div>
		<section class="community">
			<h1>Community</h1>
				<p> You will have at least one instructor walking you through each workout, and several classmates that help you, encourage you and most of all, hold you accountable.</p>
				<p>You're not just signing up for a gym, you're building a support system</p>
		</section>

	<div id="Pricing"></div>
		<section class="pricing">
			<h1>Pricing</h1>
				<ul class="no-bullets">
					<li>
						Pay per workout - $20
					</li>
									<li>
						10 workouts per month - $100
					</li>
									<li>
						15 workouts per month - $150
					</li>
									<li>
						Unlimited - $165/month
					</li>
				</ul>
		</section>
	
	<div id="Location"></div>
		<section class="location">
			<h1>Location</h1>
				<ul id="address">
						<li>
							712 Wilson Road South <br>
							Oshawa, Ontario
						</li>
					<a href="tel:+19054405264">
						<li>
							905.440.5264
						</li>
					</a>
					<a href="mailto:cam@crossfitoshawa.com">
						<li>
							getfit@crossfitoshawa.com
						</li>
					</a>
				</ul>
					<iframe id ="map" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2875.7189195560613!2d-78.835827!3d43.882374999999996!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89d502d2565efbcd%3A0x6aedeab76df8989c!2sCrossFit+Oshawa!5e0!3m2!1sen!2sca!4v1425007207794" width="400" height="300" frameborder="0" style="border:0"></iframe>
		</section>
	
	<div id="Started"></div>
		<section class="get-started">
			<h1>Get Started</h1>
				<form action="index.html" method="post">
	          		<h3>Contact Us</h3>
	          
	          	<fieldset>
		          
		            <label for="name">Name:</label>
		              <input type="text" id="name" name="user_name">
		            
		            <label for="mail">Email:</label>
		              <input type="email" id="mail" name="user_email">

    			</fieldset>

      			</form>
        			<button type="submit">Submit</button>


		</section>
</body>

<footer>
	<div class="social">
			<a href="https://www.facebook.com/CrossFitOshawa" target="_blank">
				<div class="facebook link"></div>
					</a>
				<a href="https://twitter.com/CrossFitOshawa" target="_blank">
				<div class="twitter link"></div>
					</a>
				<a href="https://instagram.com/crossfit_oshawa" target="_blank">
				<div class="instagram link"></div>
					</a>
		</div>
	
<!-- 	<p>Copyright: Crossfit Oshawa 2015</p>
		<p>All Right Reserved</p> -->
</footer>
</html>
