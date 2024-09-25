<head>
	<meta charset="UTF-8" />
	<link rel="stylesheet" href="../CSS/CoolStuff.css" />
	<script src="../JS/CoolStuff.js" defer></script>
	<link rel="icon" type="image/png" href="../Images/bicyclePNG.png" />
	<title>Ashwin Kaushik</title>
</head>

<body>
	<h1>Cool Stuff</h1>
	<table id="navTable">
		<thead>
			<tr>
				<th><a href="PersonalProjects.html">Personal Projects</a></th>
				<th><a href="AucklandResume.html">Resume</a></th>
				<th><a href="Main.html">Welcome</a></th>
				<th><a href="RecentTrips.html">Recent Trips</a></th>
				<th><a href="CoolStuff.html">Cool Stuff</a></th>
			</tr>
		</thead>
	</table>
	<main>
		<div id="bicycles">
			<img src="\FrontEnd\static\MoxieSkypark.jpg" class="horizontalPic" />
			<p>I like bikes</p>
		</div>
		<div id="snowboards">
			<img src="\FrontEnd\static\WhistlerOlympicSign.jpg" class="horizontalPic" />
			<p>I like snowboarding</p>
		</div>
		<div id="dogs">
			<img src="\FrontEnd\static\CookieAndLuna.jpg" class="verticalPic" />
			<p>I like my dog</p>
		</div>
	</main>
	<div id="Multiply">
		<div id="Num1">
			<button id="addButton">Add</button>
			<p id="count">0</p>
			<button id="subtractButton">Subtract</button>
		</div>
		<div id="Num2">
			<button id="addButton2">Add</button>
			<p id="count2">0</p>
			<button id="subtractButton2">Subtract</button>
		</div>
		<div id="MultOrDiv">
			<button id="mult">Multiply!</button>
			<p id="answer">0</p>
			<button id="divide">Divide!</button>
		</div>
	</div>
	<footer>
		<div class="social-links">
			<a href="https://www.linkedin.com/in/ashwin-kaushik-980511162/" class="social-icon"
				>LinkedIn</a
			>
			<a href="https://github.com/ashwinkodes" class="social-icon">GitHub</a>
		</div>
		<p>&copy; 2024 Ashwin Kaushik. All rights reserved.</p>
	</footer>
</body>

<style>
	/* General styles */
	body {
		font-family: Arial, sans-serif;
		line-height: 1.6;
		margin: 0;
		padding: 0;
		color: #333;
	}

	/* Header styles */
	h1 {
		text-align: center;
		margin: 1rem 0;
	}

	#navTable {
		width: 100%;
		border-collapse: collapse;
		margin-bottom: 1rem;
	}

	#navTable th {
		padding: 0.5rem;
	}

	#navTable th a {
		text-decoration: none;
		color: #333;
	}

	main {
		display: flex;
		justify-content: center;
		align-items: flex-start;
		gap: 20px;
		padding: 20px;
		flex-wrap: wrap;
	}

	main > div {
		display: flex;
		flex-direction: column;
		align-items: center;
		max-width: 300px;
		background-color: #f0f0f0;
		border-radius: 10px;
		padding: 15px;
		box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
	}

	#Num1,
	#Num2,
	#MultOrDiv {
		display: flex;
		flex-direction: row;
		align-items: space-between;
		justify-content: center;
		margin-right: auto;
		margin-left: auto;
	}

	.horizontalPic {
		width: 100%;
		height: 200px;
		object-fit: cover;
		border-radius: 8px;
	}

	.verticalPic {
		width: 100%;
		height: 300px;
		object-fit: cover;
		border-radius: 8px;
	}

	main p {
		margin-top: 10px;
		text-align: center;
		font-size: 16px;
		color: #333;
	}

	/* Footer styles */
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
