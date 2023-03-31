<script>
	import Projectcard from './Projectcard.svelte';
</script>

<div class="container">
	<h1>A little sunrise goes a long way</h1>

	<div class="portfoliosection">
		<div class="Column1">
			<Projectcard title="theGuardian" SRC="JDSJDJ" Projectcard category="UX/UI" />
			<Projectcard title="theGuardian" SRC="JDSJDJ" Projectcard category="UX/UI" />
			<Projectcard title="theGuardian" SRC="JDSJDJ" Projectcard category="UX/UI" />
		</div>

		<div class="Column2">
			<h1>Skills</h1>
			<ul>
				<li><a href="/Branding">Branding</a></li>
				<li><a href="/Branding">Digital & web</a></li>
				<li><a href="/Branding">Illustrations</a></li>
				<li><a href="/Branding">Photography</a></li>
			</ul>
		</div>

		<div class="Column2">
			<h1>Skills</h1>
			<ul>
				<li><a href="/Branding">Branding</a></li>
				<li><a href="/Branding">Digital & web</a></li>
				<li><a href="/Branding">Illustrations</a></li>
				<li><a href="/Branding">Photography</a></li>
			</ul>
		</div>
	</div>
</div>

<style lang="scss">
	.container {
		background-color: #f6eee4;
		min-height: 100vh;
		min-width: 100%;
		background-image: url('/greentriangle.svg');
		background-repeat: no-repeat;
		background-position: 75% 100%;
		border-top: 1px solid #fefbf1;
		overflow: hidden; //this is important but I don't know why
		padding: 80px;
	}

	.portfoliosection {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
	}

	h1 {
		color: #121215;
		font-family: 'Uxum';
		font-size: 100px;
		font-weight: 100;
		max-width: 80%;
	}

	p {
		color: #121215;
		font-family: 'Uxum';
		font-size: 24px;
		font-weight: lighter;
		line-height: 150%;
		max-width: 80%;
	}

	li {
		font-family: 'Uxum';
		font-size: 50px;
		border-bottom: 1px solid #121215;
		font-weight: lighter;
		padding: 20px 0 20px 48px;
		background-image: url('/arrowright.svg');
		background-repeat: no-repeat;
		background-position: 0% 50%;
		a {
			text-decoration: none;
			color: #121215;
		}

		&:hover {
			margin-left: 32px;
		}
		transition: margin-left ease-in-out 0.4s;
	}

	ul {
		border-top: 1px solid #121215;
		list-style: none;
		margin: 0;
		padding: 0;
		max-width: 80%;
	}
</style>
