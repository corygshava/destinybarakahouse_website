<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Destiny Baraka House - A blessing to the nations</title>

	<link rel="stylesheet" type="text/css" href="css/coryG_base.css">
	<link rel="stylesheet" type="text/css" href="css/common.css">
	<link rel="stylesheet" type="text/css" href="css/w3.css">
	<link rel="stylesheet" type="text/css" href="css/fa-all.css">
	<link rel="stylesheet" type="text/css" href="css/mafonts.css">
	<link rel="stylesheet" type="text/css" href="css/s-autoforms.css">
	<link rel="stylesheet" type="text/css" href="css/coryG_UIOps.css">

	<script src="js/coryG_UIOps.js"></script>
	<script src="js/SuperScript.js"></script>
	<script src="js/toappend.js"></script>
	<script src="js/customalerter.js"></script>
	<script src="js/utilities.js"></script>
</head>
<body>
	<!-- Navigation -->
	<nav class="w3-hided">
		<div class="navcon">
			<div class="logo">
				<a href="#" class="logo">Destiny Baraka House</a>
			</div>

			<div class="navlinks" id="sitelinks" data-visibledata="0,0,1">
				<a href="#services" class="active">About us</a>
				<a href="#work">programmes</a>
				<a href="#pricing">Projects</a>
				<a href="#contact">Contact</a>
			</div>

			<div>
				<a href="#contact" class="btn cta-btn" data-toggler=".mymodal" data-onshow="flex">
					<i class="fa fa-phone"></i>
					<span data-visibledata="0,0,1">Reach out</span>
					<span data-visibledata="1,1,0">inquiry</span>
				</a>
			</div>

			<div class="hamburger smallmenu" id="hamburger" data-visibledata="0,0,0">
				<a><i class="fa fa-bars"></i></a>
			</div>
		</div>
	</nav>

	<!-- landing page content -->
	<div class="content">
		<div class="fullpage_slides" id="actualtimer" style="display: none">
			<img src="images/landing_slides/slide1.jpg" class="slideimg">
			<div class="theoverlay">
				<div class="mycontent">
					<h2 class="h1" data-content="institution-name">Destiny baraka house</h2>
					<p class="cw-description text-sm">
						We are a faith-driven mission organization dedicated to spreading the Gospel, empowering local communities, and supporting humanitarian efforts around the world through love, service, and sustainable outreach.<br>
					</p>
					<b class="h3">Available in: </b>

					<div class="smallcard-group" id="timeholder">
						<div class="smallcard w3-animate-zoom">
							<div class="h2 themetxt" id="days">0</div>
							<div class="label">Days</div>
						</div>
						<div class="smallcard w3-animate-zoom">
							<div class="h2 themetxt" id="hours">00</div>
							<div class="label">Hours</div>
						</div>
						<div class="smallcard w3-animate-zoom">
							<div class="h2 themetxt" id="minutes">00</div>
							<div class="label">Minutes</div>
						</div>
						<div class="smallcard w3-animate-zoom">
							<div class="h2 themetxt" id="seconds">00</div>
							<div class="label">Seconds</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<div class="fullpage_slides" id="showcase" style="display: none">
			<img src="images/landing_slides/slide1.jpg" class="slideimg" id="slidimg">
			<div class="theoverlay" data-role="slideshow">
				<div class="mycontent">
					<span class="h2 heading"></span>
					<p class="desc"></p>
					<div class="actions"></div>
				</div>
			</div>
			<div class="controller">
				<div class="slidecount"></div>
				<div class="progress"><div class="bar" style="width:0%"></div></div>
			</div>
		</div>

		<div class="notetxt w3-display-topleft" style="z-index: 200;">
			<span class="themetxt">WORK IN PROGRESS</span>
		</div>
	</div>

	<script>
		let slideshowimg = undefined;
		let imgsetup = false;
		
		if((startCountdown(launchdate).toUpperCase() == "PASSED!")){
			actualtimer.style.display = 'none';
			showcase.style.display = 'block';
		} else {
			actualtimer.style.display = 'block';
			showcase.style.display = 'none';
			makecountdown('#timeholder');
		}

		function play_slide(data,linger) {
			const holder = document.querySelector('[data-role=slideshow]');

			if(holder != undefined){
				let hed = holder.querySelector('.heading');
				let desc = holder.querySelector('.desc');
				let slideimg = document.querySelector('#slidimg');

				if(!imgsetup){
					imgsetup = true;
					slideimg.addEventListener('load',() => {
						slideimg.animate([...entre],{...timing,duration: 1200});
					})
				}
				// let actions = holder.querySelector('.actions');
				let deltime = 250;

				hed.animate([...opac].reverse(),{...timing,duration: 200});
				desc.animate([...opac].reverse(),{...timing,duration: 200});
				slideimg.animate([...opac].reverse(),{...timing,duration: 200});


				hed.animate(slideupAnim2,{...timing,delay: deltime})
				deltime += 200;
				desc.animate(slideupAnim,{...timing,delay: deltime})

				setTimeout(() => {
					slideimg.src = `images/landing_slides/slide${data.imageid}.jpg`;
					hed.textContent = data.title;
					desc.innerHTML = data.description;
				},200);

				setTimeout(() => {
					// hed.animate(slideupAnim,{...timing,delay: deltime,direction: "backwards"})
					deltime += 200;
					// desc.animate(slideupAnim,{...timing,delay: deltime,direction: "backwards"})
				},linger);
			}
		}

		function play_controller(id,dur) {
			const controls = document.querySelector('.controller');
			let prgtext = controls.querySelector('.slidecount');
			let prgbar = controls.querySelector('.progress>.bar');

			prgtext.animate(slideupAnim2,timing);
			prgbar.animate(longen,{...timing,duration: dur});

			setTimeout(() => {
				let prg = id % sections.length;
				prgtext.innerHTML = `${prg + 1} / <b>${sections.length}</b>`;
			})
		}

		function runslides(){
			let slideduration = 3000,id = 0;
			play_slide(sections[id],slideduration);
			play_controller(id,slideduration);

			setInterval(() => {
				id += 1;
				play_slide(sections[id % sections.length],slideduration);
				play_controller(id,slideduration);
			},slideduration + timing.duration);
		}

		window.addEventListener('load',() => {
			slideshowimg = document.querySelector('.slideimg');
			// alert_success("all elements loaded!");
			runslides();
		})

		// mute navlinks
		sitelinks.querySelectorAll('a').forEach((el,id) => {
			el.addEventListener('click',() => {
				alert_warning("work in progress, this feature isnt available yet");
			})
		})
	</script>

	<!-- Footer -->
	<footer class="w3-bottom">
		<p>&copy; 2025 Destiny Baraka House.<br> A blessing to the nations</p>
	</footer>

	<!-- Signup Modal -->

	<div id="signupModal" class="mymodal" data-shown="0" style="display:none">
		<div class="modal-content modetxt md w3-animate-zoom panelbg">
			<span class="btn w3-transparent w3-right" onclick="toggleShowB('.mymodal','flex','none')"><i class="fa fa-times"></i></span>
			<span class="h2 w3-center">Contact us</span>
			<form onsubmit="handleSubmit(event)" class="s-autoform-2">
				<div class="form-group">
					<label for="name">Full Name</label>
					<input type="text" id="name" name="name" required>
				</div>
				<div class="form-group">
					<label for="email">Email Address</label>
					<input type="email" id="email" name="email" required>
				</div>
				<div class="form-group">
					<label for="phone">Phone Number</label>
					<textarea name="msg" rows="3"></textarea>
				</div>
				<button type="submit" class="form-button">send message <i class="fa fa-paper-plane"></i></button>
			</form>
		</div>
	</div>

	<script>
		// Modal Functions
		function openModal() {
			document.getElementById('signupModal').style.display = 'block';
		}

		function closeModal() {
			document.getElementById('signupModal').style.display = 'none';
		}

		// Close modal when clicking outside
		window.onclick = function(event) {
			const modal = document.getElementById('signupModal');
			if (event.target == modal) {
				modal.style.display = 'none';
			}
		}

		// Form Submission
		function handleSubmit(event) {
			event.preventDefault();
			toggleShowB('.mymodal','flex','none');

			// Show success message
			alert_success('Thank you for signing up! We\'ll be in touch soon.');

			// Reset form
			event.target.reset();
		}

		// Smooth scroll for navigation links
		document.querySelectorAll('a[href^="#"]').forEach(anchor => {
			anchor.addEventListener('click', function (e) {
				e.preventDefault();
				const target = document.querySelector(this.getAttribute('href'));
				if (target) {
					target.scrollIntoView({
						behavior: 'smooth',
						block: 'start'
					});
				}
			});
		});
	</script>
</body>
</html>