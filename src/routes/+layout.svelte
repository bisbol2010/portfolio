<header>
	<a href="/">
		<img alt="logo" src="/aboakinlogo.svg" />
	</a>
	<nav>
		<a href="/"> Home</a> <a href="/projects"> projects</a> <a href="/contact"> contact</a>
	</nav>
</header>

<slot />

<style lang="scss">
	:global(body) {
		background-color: #1c1c20;
	}
	h1 {
		color: black;
		font-family: 'DM Sans', sans-serif;
		font-size: 100px;
	}
	header {
		display: flex;
	}

	nav {
		display: flex;
		justify-content: flex-end;
		flex: 1;
	}

	nav a {
		color: #fefbf1;
		font-family: 'uxum';
		font-size: 70px;
		padding: 20px 20px;
		text-decoration: none;
		&:hover {
			color: #fbff58;
			transform: scale(1.1);
		}
		transition: color ease-in-out 0.4s, transform ease-in-out 0.4s;
	}
</style>
