<script>
	export let title = '';
	export let src = '';
	export let category = '';
</script>

<div>
	<h2>
		{title}
	</h2>
	<img {src} />
	<p>
		{category}
	</p>
</div>
