<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';
	import Avatar from '$lib/avatar.svelte';
	import '../global.scss';
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<header class="row">
	<p>Leo Ericson</p>
	<div class="row">
		<!--<a href="#portfolio">Portfolio</a>-->
		<a href="#experience">Experience</a>
		<a href="#education">Education</a>
	</div>
</header>

<section class="row lander full-height">
	<Avatar />

	<div data-aos="fade-right">
		<h1>Leo <span class="active">Ericson</span></h1>
		<p><a href="mailto:leo@ericson.gg">leo@ericson.gg</a></p>
		<p>
			I am a developer and system admin with a passion for web development, app development,
			networking and servers. I enjoy problem-solving and collaborating with a team to achieve a
			common goal.
		</p>

		<div class="btn-list row">
			<a
				href="https://www.linkedin.com/in/leoericson/"
				class="square"
				target="_blank"
				rel="noopener nofollow"
				aria-label="See my LinkedIn"
			>
				<i class="fa-brands fa-linkedin-in" />
			</a>
			<a
				href="https://github.com/LeoEricson/"
				class="square"
				target="_blank"
				rel="noopener nofollow"
				aria-label="See my GitHub"
			>
				<i class="fa-brands fa-github" />
			</a>
			<a href="mailto:leo@ericson.gg" target="_blank" rel="noopener nofollow">
				<i class="fa-regular fa-envelope" />
				Contact me
			</a>
		</div>
	</div>
</section>

<!--
<section class="list" id="portfolio">
	<h2>Portfolio</h2>

	<div class="row" data-aos="fade-right">
		<img src="rikstrafiken.png" alt="" style="; border-radius: 64px;" />
		<div>
			<h3>Rikstrafiken</h3>
			<p>SwiftUI based iOS app with NestJS backend.</p>

			<div class="btn-list row">
				<a href=""><i class="fa-brands fa-github" /> Source</a>
				<a href=""><i class="fa-brands fa-app-store" /> App Store</a>
			</div>
		</div>
	</div>
</section>
-->

<section class="list" id="experience">
	<h2>Experience</h2>

	<div class="experience" data-aos="fade-right">
		<h3>Advania Sweden - Managed Services Provider</h3>
		<div>
			<div class="row">
				<h4>System Consultant</h4>
				<p>January 2025 — Current</p>
			</div>

			<ul>
				<li>Maintain and continuously improve central systems and customer environments.</li>
                <li>Design and establish new systems to improve workflow and efficiency.</li>
				<li>Develop processes and security guidelines.</li>
			</ul>

			<br />

			<div class="row">
				<h4>Service Desk Technician</h4>
				<p>October 2023 — December 2024</p>
			</div>

			<ul>
				<li>Respond to first line support issues through phone and ServiceNow.</li>
				<li>Continuously improve documentation and IT-processes.</li>
				<li>Coach the service desk team to achieve a higher technical level.</li>
			</ul>
		</div>
	</div>

	<div class="experience" data-aos="fade-right">
		<h3>Justifi Network, New York (Remote)</h3>
		<div>
			<div class="row">
				<h4>Technical Lead</h4>
				<p>February 2022 — October 2023</p>
			</div>

			<ul>
				<li>Lead the techincal team consisting of network engineers, system admins and developers.</li>
				<li>Responsibilities include achieving KPIs, quality assurance, and development.</li>
			</ul>

			<br />

			<div class="row">
				<h4>System Administrator</h4>
				<p>October 2021 — February 2022</p>
			</div>

			<ul>
				<li>Server operations, handling a wide range of issues through FLS (First line support).</li>
				<li>Conducting troubleshooting and resolving problems.</li>
				<li>Deployed, configured and maintained virtual machines and containers</li>
				<li>Deployed internal DNS and an internal certificate authority</li>
			</ul>
		</div>
	</div>

	<div class="experience" data-aos="fade-right">
		<h3>SPACE Academy, Stockholm</h3>
		<div>
			<div class="row">
				<h4>Education Architect</h4>
				<p>April 2023 — September 2023</p>
			</div>
			<ul>
				<li>Lead tech and design courses and activites for children and young adults</li>
				<li>Develop material and revise based on feedback</li>
				<li>Lead and mentor a team of educators</li>
				<li>Develop hackathons and techincal solutions for SPACE Academy</li>
				<li class="award">
					<i class="fa-solid fa-trophy active" /> Helped earn SPACE Academy the Competence Award at TechSverige
					2023
				</li>
			</ul>

			<br />

			<div class="row">
				<h4>Senior Educator</h4>
				<p>October 2022 — April 2023</p>
			</div>
			<ul>
				<li>Lead courses and activites for children and young adults</li>
			</ul>
		</div>
	</div>

	<div class="experience" data-aos="fade-right">
		<h3>PostNord Sverige, (Järfälla)</h3>

		<div>
			<div class="row">
				<h4>Terminal Tractor Driver</h4>
				<p>February 2024 — August 2024</p>
			</div>

			<ul>
				<li>Coordination of incoming trailers and offloading.</li>
				<li>Rearranging trailers, dolly trailer etc.</li>
			</ul>

			<br />

			<div class="row">
				<h4>Postal Delivery Officer</h4>
				<p>July 2022 — September 2023</p>
			</div>
			<ul>
				<li>Handling and sorting parcels</li>
				<li>Loading and unloading parcels and pallets</li>
				<li>Registering departures and arrivals</li>
			</ul>
		</div>
	</div>

	<div class="experience" data-aos="fade-right">
		<h3>Ljud- och Bildskolan Kreativa Gymnasiet, Solna</h3>

		<div>
			<div class="row">
				<h4>IT-Administration Intern</h4>
				<p>July 2022 — June 2023</p>
			</div>
			<ul>
				<li>Managed and troubleshooted school computers and systems</li>
				<li>Repaired hardware issues and administered system updates and changes</li>
				<li>Maintained documentation</li>
			</ul>
		</div>
	</div>
</section>

<section class="list" id="education">
	<h2>Education</h2>

	<div data-aos="fade-right">
		<div class="row">
			<h3>High School Diploma, Technical Program</h3>
			<p>2020 — 2023</p>
		</div>
		<p>Ljud- och Bildskolan Kreativa Gymnasiet, Solna</p>
		<p>Systems & Web Development</p>
	</div>
</section>

<footer>
	<p>
		Made with ☕ by <a href="/">Leo Ericson</a>
	</p>
</footer>
