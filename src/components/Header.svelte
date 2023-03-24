<div class="header">
	<div class="textrow">
		<div class="scrollleft">
			BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS
			ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS ILLUSTRATIONS BRANDING, DIGITAL, UI
			&UX, ILLUSTRATIONS ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS ILLUSTRATIONS
			BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS ILLUSTRATIONS BRANDING, DIGITAL, UI &UX,
			ILLUSTRATIONS ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS ILLUSTRATIONS BRANDING,
			DIGITAL, UI &UX, ILLUSTRATIONS ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS
			ILLUSTRATIONS BRANDING, DIGITAL, UI &UX, ILLUSTRATIONS
		</div>
	</div>

	<div class="textrow">
		<div class="scrollright">
			Design is an Adventure Design is an Adventure Design is an Adventure Design is an Adventure
			Design is an Adventure Design is an Adventure Design is an Adventure Design is an Adventure
			Design is an Adventure Design is an Adventure Design is an Adventure Design is an Adventure
			Design is an Adventure
		</div>
	</div>

	<div class="textrow">
		<div class="scrollleft">
			come along with me, lets gets on with it come along with me, lets gets on with it come along
			with me, lets gets on with it come along with me, lets gets on with it come along with me,
			lets gets on with it come along with me, lets gets on with it come along with me, lets gets on
			with it come along with me, lets gets on with it come along with me, lets gets on with it come
			along with me, lets gets on with it come along with me, lets gets on with it come along with
			me, lets gets on with it
		</div>
	</div>
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
		border-bottom: 1px solid #fefbf1;
		padding: 2rem 0;
		position: relative;
		display: flex;
	}

	@keyframes scrolltextleft {
		0% {
			transform: translateX(-1000%);
		}
		100% {
			transform: translateX(0);
		}
	}

	@keyframes scrolltextright {
		0% {
			transform: translateX(0);
		}
		100% {
			transform: translateX(-1000%);
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
		top: 0;
		transform: translateX(100%);
		width: 100%;
		white-space: nowrap;
		animation: scrolltextleft 300s linear infinite;
	}

	.scrollright {
		top: 0;
		transform: translateX(100%);
		width: 100%;
		white-space: nowrap;
		animation: scrolltextright 300s linear infinite;
	}

	.delay {
		animation-delay: 15s;
	}
</style>
