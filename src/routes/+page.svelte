<script>
	import DiGithubBadge from 'svelte-icons/di/DiGithubBadge.svelte';
	import FaLinkedin from 'svelte-icons/fa/FaLinkedin.svelte';
</script>

<div class="container">
	<h1>TUDOR EVANS</h1>
	<div class="flex">
		<div class="icon">
			<a href="https://www.linkedin.com/in/tudor-evans-5a2232151/"><FaLinkedin /></a>
		</div>
		<div class="icon">
			<a href="https://github.com/TudorLEvans"><DiGithubBadge /></a>
		</div>
	</div>		
	<img  class="profile-picture" alt="Tudor Evans" src="tudor-evans.jpg"/>
	<p class="caption">This is me in Exeter, 2021, enjoying a pint by the canal</p>
	<h2>About Me</h2>
	<p class="annotation">
		I'm a full-stack software engineer | planner | designer - whatever I need to do to make
		interesting things. I want to work on projects where meaningful products get made.
	</p>
	<h3>Education</h3>
	<p>
		I studied at the University of Cambridge (Jesus College) and graduated with a BA in Natual
		Science (Physics) and MSci in Natural Science (History and Philosophy of Science).
	</p>
	<h3>Career</h3>
	<p class="annotation">
		I work in Golang, Javascript/Typescript and Python primarily. I have some experience with Lua,
		Rust and C++.
	</p>
	<p>
		I started my career at IBM in 2019 where I worked as a Technology Consultant. I progressed to
		Senior Technology Consultant in 2021.
	</p>
	<p>
		After IBM, I moved to Speechmatics (an ASR startup in Cambridge) as a Software Engineer in 2022.
		I have since progressed to Senior Software Engineer (start of 2023).
	</p>
	<h2>Music</h2>
	<p class="annotation">
		Please note, I do not own the copyright to those pieces listed which I did not compose.
		Feel free to use, copy and distribute this music for personal entertainment and educational
		purposes only. If you have any issues concerning the copyright of these pieces, please contact
		me.
	</p>
	<p>
		I've been playing guitar for many years now - originally electric, but now primarily classical.
		I play in a casual Jazz band in Cambridge with some friends, and feel that music is a great way
		to have fun and connect with people. Sometimes, I like to transcribe music for our band to play,
		or even write my own compositions. This is s small selection of those pieces.
	</p>
	<ul>
		<h3>Spain</h3>
		<li>
			<a href="spain-chick-corea-for-c-instruments.pdf"
				>Spain (old version) by Chick Corea (for C instruments)</a
			>
		</li>
		<li><a href="spain-new-in-d.pdf">Spain in B minor</a></li>
		<li><a href="spain-new-in-e.pdf">Spain in C# minor</a></li>
		<li><a href="spain-new-in-c.pdf">Spain in A minor</a></li>
		<h3>Misc</h3>
		<li><a href="mack-the-knife-ideas.pdf">Mack the Knife ideas</a></li>
		<li><a href="the-third-man-c-instruments.pdf">The Third Man Theme (for C instruments)</a></li>
		<li><a href="the-third-man-Bb-instruments.pdf">The Third Man Theme (for Bb instruments)</a></li>
		<li><a href="the-third-man-Eb-instruments.pdf">The Third Man Theme (for Eb instruments)</a></li>
		<li><a href="el-choclo-for-c.pdf">El Choclo (for C instruments)</a></li>
		<li><a href="el-choclo-for-Bb.pdf">El Choclo (for Bb instruments)</a></li>
		<li>
			<a href="he-was-a-friend-of-mine.pdf"
				>He Was a Friend of Mine (guitar accompaniment arrangement)</a
			>
		</li>
	</ul>
	<ul>
		<h3>Riverside Maxixe</h3>
		<li><a href="riverside-maxixe-in-d.pdf">Riverside Maxixe in D</a></li>
		<li><a href="riverside-maxixe-in-g-alt.pdf">Riverside Maxixe in G</a></li>
		<li><a href="riverside-maxixe-in-a-alt.pdf">Riverside Maxixe in A</a></li>
		<li><a href="riverside-maxixe-in-e-alt.pdf">Riverside Maxixe in E</a></li>
		<h3>Jungle Sauce</h3>
		<li><a href="jungle-sauce-in-a.pdf">Jungle Sauce in A</a></li>
		<li><a href="jungle-sauce-in-b.pdf">Jungle Sauce in B</a></li>
		<li><a href="jungle-sauce-in-f-sharp.pdf">Jungle Sauce in F#</a></li>
	</ul>
</div>

<style>
	@font-face {
		font-family: Baskerville;
		src: url(fonts/LibreBaskerville-Regular.ttf);
		font-weight: normal;
	}
	@font-face {
		font-family: Baskerville;
		src: url(fonts/LibreBaskerville-Bold.ttf);
		font-weight: bold;
	}
	@font-face {
		font-family: Baskerville;
		src: url(fonts/LibreBaskerville-Italic.ttf);
		font-style: italic;
	}

	@font-face {
		font-family: Garamond;
		src: url(fonts/EBGaramond-Italic-VariableFont_wght.ttf);
		font-style: italic;
	}
	@font-face {
		font-family: Garamond;
		src: url(fonts/EBGaramond-VariableFont_wght.ttf);
	}

	p,
	a,
	li {
		font-family: Garamond;
		font-weight: 300;
		font-size: 1rem;
		max-width: 800px;
		line-height: 1.5rem;
	}
	a {
		text-decoration: none;

	}
    a:visited {
        color: #1975d1;
    }
	li {
		font-style: italic;
		letter-spacing: normal;
		display: block;
	}

	h1 {
		font-size: 3rem;
		font-weight: 500;
		letter-spacing: 0.3rem;
		margin-bottom: 20px;
	}
	h2 {
		font-family: Garamond;
		font-weight: 400;
		font-style: italic;
		font-size: 1.8rem;
		margin-bottom: 10px;
	}
	h3 {
		font-family: Garamond;
		font-weight: 600;
		font-size: 1.2rem;
		margin-bottom: 10px;
	}

	ul {
		line-height: 1.5rem;
		display: inline-block;
		justify-content: center;
	}

	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		width: 80vw;
		min-width: fit-content;
		align-self: center;
        padding-bottom: 40px;
		animation: fadeIn 0.5s;
		background-color: white;
	}

	@keyframes fadeIn {
		0% {
			opacity: 0;
		}
		100% {
			opacity: 1;
		}
	}

	.icon {
		width: 2rem;
		height: 2rem;
        color: #1975d1;
    }
    .flex {
        display: flex;
        gap: 1rem;
        margin-bottom: 40px;
    }
	.profile-picture {
		margin-top: 10px;
		width: 300px;
		height: 300px;
		border-radius: 100%;
		object-fit: cover;
	}

	.caption {
		font-style: italic;
		font-size: 0.8rem;
		color: rgb(110, 110, 110);
	}
	.annotation {
        color: #1975d1;
		font-style: italic;
		font-size: 0.8rem;
	}
</style>
