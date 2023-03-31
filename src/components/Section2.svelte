<div class="section2">
	<div class="Column1">
		<h1>A little sunrise goes a long way</h1>
		<p>
			I am a London based multi-disciplinarian Designer with 7 years of experience. I love to take a
			project from idea to completion by carefully going through all of the stages including
			research, UX(user experience) and UI(User Interphase design) I have experience in print,
			digital, illustrations & photography. In my spare time, I'm learning to code (If you’re seeing
			this, then I have successfully coded it :)
		</p>
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

<style lang="scss">
	.section2 {
		background-color: #ffcc29;
		min-height: 100vh;
		min-width: 100%;
		background-image: url('/greentriangle.svg');
		background-repeat: no-repeat;
		background-position: 75% 100%;
		border-top: 1px solid #fefbf1;
		overflow: hidden;
		display: grid;
		grid-template-columns: 1.2fr 1fr;
		padding: 80px;
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
