<script>
	export let title = '';
	export let src = '';
	export let category = '';
	export let margintop = '0';
	export let marginbottom = '0';
</script>

<div style="margin-top:{margintop}; margin-bottom:{marginbottom};">
	<h2>
		{title}
	</h2>
	<div class="image"><img {src} /></div>
	<p>
		{category}
	</p>
</div>

<style lang="scss">
	h2 {
		color: #f0353c;
		font-family: 'Uxum';
		font-size: 48px;
		font-weight: 100;
		max-width: 100%;
		background-image: url('/arrowrightred.svg');
		background-repeat: no-repeat;
		background-position: 100% 50%;
		&:hover {
			margin-right: 32px;
		}
		transition: margin-right ease-in-out 0.4s;
	}

	p {
		color: #f0353c;
		font-family: 'Uxum';
		font-size: 16px;
		font-weight: 100;
		max-width: 80%;
	}

	.image {
		img {
			max-width: 100%;
		}
		background-color: #ffffff;
	}
</style>
