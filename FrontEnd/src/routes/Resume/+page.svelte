<head>
	<meta charset="UTF-8" />
	<title>Resume</title>
	<link rel="stylesheet" href="../CSS/Resume.css" />
	<link rel="icon" type="image/png" href="../Images/resumePNG.png" />
</head>

<body>
	<p class="name">Ashwin Kaushik</p>

	<table class="nav-table">
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
	<div class="resume-container">
		<p class="contact">
			<a href="mailto:ashwin22kaushik@gmail.com" class="contact-link" target="_blank"
				>Auckland Central, NZ • 0225053741 •
			</a>
			<a href="mailto:ashwin22kaushik@gmail.com" class="contact-link" target="_blank"
				>ashwin22kaushik@gmail.com</a
			>
		</p>

		<h1 class="section-title">Professional Summary</h1>
		<p class="summary">
			Current Masters of IT student with hands-on technical and customer-facing experience.
			Combining technical knowledge from a BS in Information Systems with practical skills in
			analyzing business solutions and managing online retail operations.
		</p>

		<h1 class="section-title">Skills</h1>
		<ul id="skills">
			<li class="skill-item">Web Development (HTML, CSS) - Financial Modeling</li>
			<li class="skill-item">Data Analysis (R, Python, Tableau) - Microsoft Office</li>
			<li class="skill-item">Server Management (Proxmox, DNS, TCP/IP) - Systems Analysis/Design</li>
		</ul>

		<h1 class="section-title">Education</h1>
		<h2 class="education-title">M.S. Information Technology | University of Auckland</h2>
		<p class="education-duration">July 2024 - (estimated) June 2026</p>
		<ul id="education-ms">
			<li class="education-item">Coursework in web development and industry programming</li>
		</ul>

		<h2 class="education-title">B.S. Information Systems | University of California, Riverside</h2>
		<p class="education-duration">September 2019 - June 2022</p>
		<ul id="education-bs">
			<li class="education-item">
				Coursework in data mining, database management, business simulation, systems
				analysis/design, finance, accounting
			</li>
			<li class="education-item">
				Projects on relational databases, Tableau reporting, Excel forecasting, Gantt charts, pivot
				tables, data flow diagrams, and stock/company valuations
			</li>
		</ul>

		<h1 class="section-title">Work History</h1>

		<h2 class="job-title">eCommerce Manager | Summit Bicycles</h2>
		<p class="job-duration">December 2020 – June 2024</p>
		<ul id="work-summit">
			<li class="job-item">
				Lead eCommerce team; Customer outreach, order processing, &amp; fulfillment
			</li>
			<li class="job-item">Server management, inventory management, sales-based web design</li>
			<li class="job-item">
				Independently established B2B relationships with core-business component manufacturers to
				register as a certified dealer/technician
			</li>
		</ul>

		<h2 class="job-title">Solutions Analyst Intern | Nidaan Systems</h2>
		<p class="job-duration">October 2022 – February 2023</p>
		<ul id="work-nidaan">
			<li class="job-item">Design, update, and manage WordPress website/domain</li>
			<li class="job-item">
				Utilize API’s &amp; scripts through Dell’s Boomi Integration Platform to facilitate transfer
				of data between law firms and cloud services
			</li>
			<li class="job-item">
				Compose data-flow-diagrams, flowcharts, and other pertinent documentation while
				communicating directly with client teams
			</li>
		</ul>

		<h2 class="job-title">Math Tutor | Afficient Academy</h2>
		<p class="job-duration">August 2017 - April 2019</p>
		<ul id="work-afficient">
			<li class="job-item">
				Inform and communicate with customers to work through orders and answer pertinent questions
			</li>
		</ul>
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
	body {
		font-family: 'Arial', sans-serif;
		color: #333;
		line-height: 1.6;
		max-width: 800px;
		margin: 0 auto;
		padding: 20px;
		background-color: #f4f4f4;
	}

	.resume-container {
		background-color: white;
		padding: 40px;
		box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		border-radius: 5px;
	}

	.name {
		text-align: center;
		font-size: 28pt;
		font-weight: bold;
		color: #2c3e50;
		margin-bottom: 10px;
	}

	.contact {
		text-align: center;
		font-size: 12pt;
		margin-bottom: 20px;
	}

	.contact-link {
		color: #3498db;
		text-decoration: none;
	}

	.section-title {
		font-size: 18pt;
		font-weight: bold;
		color: #2c3e50;
		border-bottom: 2px solid #3498db;
		padding-bottom: 5px;
		margin-top: 30px;
		margin-bottom: 15px;
	}

	.summary {
		font-size: 12pt;
		margin-bottom: 20px;
	}

	ul {
		list-style-type: none;
		padding-left: 0;
	}

	.skill-item,
	.education-item,
	.job-item {
		padding-left: 20px;
		position: relative;
		margin-bottom: 10px;
	}

	.skill-item:before,
	.education-item:before,
	.job-item:before {
		content: '•';
		position: absolute;
		left: 0;
		color: #3498db;
	}

	.education-title,
	.job-title {
		font-size: 14pt;
		font-weight: bold;
		color: #34495e;
		margin-top: 20px;
		margin-bottom: 5px;
	}

	.education-duration,
	.job-duration {
		font-size: 10pt;
		color: #7f8c8d;
		margin-bottom: 10px;
	}

	/* Navigation styles */
	.nav-table {
		width: 100%;
		margin-bottom: 20px;
		background-color: #2c3e50;
		border-radius: 5px;
	}

	.nav-table th {
		padding: 10px;
	}

	.nav-table th a {
		text-decoration: none;
		color: white;
		font-weight: normal;
		transition: color 0.3s ease;
	}

	.nav-table th a:hover {
		color: #3498db;
	}

	/* Footer styles */
	footer {
		background-color: #2c3e50;
		color: white;
		text-align: center;
		padding: 1rem;
		margin-top: 30px;
		border-radius: 5px;
	}

	.social-links {
		margin-bottom: 1rem;
	}

	.social-icon {
		color: white;
		text-decoration: none;
		margin: 0 0.5rem;
		transition: color 0.3s ease;
	}

	.social-icon:hover {
		color: #3498db;
	}
</style>
