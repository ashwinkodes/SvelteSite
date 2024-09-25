<script>
	import { onMount } from 'svelte';
  
	let gradPhoto = '/images/GradwScotty.jpg';
	let advPhoto = '/images/BoulderCO.jpg';
	let projectPhoto = '/images/server.jpg';
  
	const hoverGradPhoto = '/images/SkyParkFriends.jpg';
	const hoverAdvPhoto = '/images/MoxieSkypark.jpg';
  
	function hoverAboutMe() {
	  gradPhoto = hoverGradPhoto;
	}
  
	function unHoverAboutMe() {
	  gradPhoto = '/images/GradwScotty.jpg';
	}
  
	function hoverAdventure() {
	  advPhoto = hoverAdvPhoto;
	}
  
	function unHoverAdventure() {
	  advPhoto = '/images/BoulderCO.jpg';
	}
  </script>
  
  <svelte:head>
	<title>Ashwin Kaushik - Portfolio</title>
  </svelte:head>
  
  <header>
	<h1>Ashwin Kaushik</h1>
	<nav>
	  <a href="/PersonalProjects">Personal Projects</a>
	  <a href="/AucklandResume">Resume</a>
	  <a href="/" class="active">Welcome</a>
	  <a href="/RecentTrips">Recent Trips</a>
	  <a href="/CoolStuff">Cool Stuff</a>
	</nav>
  </header>
  
  <div class="hero">
	<div class="hero-content">
	  <h2>Welcome to My Portfolio</h2>
	  <p>Explore my projects, adventures, and experiences</p>
	</div>
  </div>
  
  <main>
	<section class="about-me" on:mouseenter={hoverAboutMe} on:mouseleave={unHoverAboutMe}>
	  <img src={gradPhoto} alt="Graduation photo" id="GradPhoto">
	  <h2>About Me</h2>
	  <p>I'm a passionate adventurer and developer, always seeking new challenges and experiences. From mountain biking to coding, I love pushing my limits and learning new skills.</p>
	  <a href="/CoolStuff" class="button">Cool Stuff</a>
	</section>
  
	<section class="recent-adventures" on:mouseenter={hoverAdventure} on:mouseleave={unHoverAdventure}>
	  <img src={advPhoto} alt="Recent adventure" id="AdvPhoto">
	  <h2>Recent Adventures</h2>
	  <p>You can catch me outside every chance I get. Whether that be with the doggo, traveling to distant countries, cycling, or trying new foods!</p>
	  <a href="/RecentTrips" class="button">Adventures</a>
	</section>
  
	<section class="personal-projects">
	  <img src={projectPhoto} alt="Personal Projects" id="ProjectPhoto">
	  <h2>Personal Projects</h2>
	  <p>As a self-proclaimed nerd, I've spent increasing amounts of time experimenting with modern applications/technologies like Docker and HomeAssistant while implementing new hardware</p>
	  <a href="/PersonalProjects" class="button">Personal Projects</a>
	</section>
  </main>
  
  <footer>
	<div class="social-links">
	  <a href="https://www.linkedin.com/in/ashwin-kaushik-980511162/" class="social-icon">LinkedIn</a>
	  <a href="https://github.com/ashwinkodes" class="social-icon">GitHub</a>
	</div>
	<p>© 2024 Ashwin Kaushik. All rights reserved.</p>
  </footer>
  
  <style>
	:global(body) {
	  font-family: Arial, sans-serif;
	  margin: 0;
	  padding: 0;
	  box-sizing: border-box;
	}
  
	header {
	  background-color: #f0f0f0;
	  padding: 1rem;
	  text-align: center;
	}
  
	nav {
	  margin-top: 1rem;
	}
  
	nav a {
	  margin: 0 1rem;
	  text-decoration: none;
	  color: #333;
	}
  
	nav a.active {
	  font-weight: bold;
	}
  
	.hero {
	  background-image: url('/images/CheckpointHuntersPoint.jpg');
	  background-size: cover;
	  background-position: center;
	  height: 60vh;
	  display: flex;
	  align-items: center;
	  justify-content: center;
	  text-align: center;
	  color: white;
	  position: relative;
	}
  
	.hero::before {
	  content: '';
	  position: absolute;
	  top: 0;
	  left: 0;
	  right: 0;
	  bottom: 0;
	  background: rgba(0, 0, 0, 0.5);
	}
  
	.hero-content {
	  position: relative;
	  z-index: 1;
	}
  
	main {
	  display: grid;
	  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
	  gap: 2rem;
	  padding: 2rem;
	}
  
	section {
	  background-color: #f9f9f9;
	  padding: 2rem;
	  border-radius: 5px;
	}
  
	img {
	  max-width: 100%;
	  border-radius: 5px;
	  margin-bottom: 1rem;
	}
  
	.button {
	  display: inline-block;
	  background-color: #333;
	  color: white;
	  padding: 0.5rem 1rem;
	  text-decoration: none;
	  border-radius: 3px;
	  margin-top: 1rem;
	}
  
	footer {
	  background-color: #333;
	  color: white;
	  text-align: center;
	  padding: 1rem;
	}
  
	.social-links {
	  margin-bottom: 1rem;
	}
  
	.social-icon {
	  color: white;
	  text-decoration: none;
	  margin: 0 0.5rem;
	}
  </style>