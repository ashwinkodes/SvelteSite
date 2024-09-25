<head>
	<meta charset="UTF-8" />
	<link rel="stylesheet" href="../CSS/PersonalProjects.css" />
	<link rel="icon" type="image/png" href="../Images/computerPNG.png" />
	<script src="../JS/PersonalProjects.js" defer></script>
	<script src="../JS/HWData.js"></script>
	<title>Ashwin Kaushik</title>
</head>

<body>
	<h1>Personal Projects</h1>
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
		<table id="homeworkTable">
			<thead>
				<tr>
					<th>Class</th>
					<th>Assignment</th>
					<th>Date</th>
				</tr>
			</thead>
			<tbody id="tableBody">
				<tr>
					<td>CS718</td>
					<td>Assignment Part B</td>
					<td>Friday</td>
				</tr>
			</tbody>
		</table>
	</main>
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

	/* Homework table styles */
	#homeworkTable {
		width: 50%;
		margin-left: auto;
		margin-right: auto;
		border-collapse: collapse;
		text-align: center;
	}

	#homeworkTable th,
	#homeworkTable td {
		padding: 0.5rem;
		border: 1px solid #ddd;
	}
</style>
