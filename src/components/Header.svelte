<div class="header">
	<div class="textrow scrollleft">BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS</div>

	<div class="textrow scrollright">Design is an Adventure, Adventure is a Design</div>

	<div class="textrow scrollleft">come along with me, lets gets on with it</div>
</div>

<style>
	.header {
		background-color: #1c1c20;
		min-height: 100vh;
		min-width: 100%;
		background: url('purplecircle.svg') no-repeat;
		background-position: 75% 20%;
		border-top: 1px solid #fefbf1;
		overflow: hidden;
	}

	.textrow {
		font-size: 100px;
		color: #fefbf1;
		font-family: 'uxum';
		text-overflow: none;
		width: 200vw;
		border-bottom: 1px solid #fefbf1;
		padding: 2rem 0;
	}

	@keyframes scrolltextleft {
		from {
			transform: translateX(0);
		}

		to {
			transform: translateX(-100%);
		}
	}

	@keyframes scrolltextright {
		from {
			transform: translateX(-100%);
		}

		to {
			transform: translateX(0);
		}
	}

	@font-face {
		font-family: 'uxum';
		font-style: normal;
		font-weight: bold;
		src: url('fonts/UxumGrotesque-Bold.woff') format('woff');
	}

	@font-face {
		font-family: 'uxum';
		font-style: normal;
		font-weight: normal;
		src: url('fonts/UxumGrotesque-Regular.woff') format('woff');
	}

	@font-face {
		font-family: 'uxum';
		font-style: italic;
		font-weight: bold;
		src: url('fonts/UxumGrotesqueItalic-Bold.woff') format('woff');
	}

	@font-face {
		font-family: 'uxum';
		font-style: italic;
		font-weight: normal;
		src: url('fonts/UxumGrotesqueItalic-Regular.woff') format('woff');
	}

	.scrollleft {
		animation: scrolltextleft 10s;
		animation-iteration-count: infinite;
		animation-direction: alternate;
	}

	.scrollright {
		animation: scrolltextright 10s;
		animation-iteration-count: infinite;
		animation-direction: alternate;
	}
</style>
