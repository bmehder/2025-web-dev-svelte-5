<script>
	let {
		src,
		heading,
		description = 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Lorem, ipsum.',
		href = '/blog',
	} = $props()
</script>

<div class="flow bg-white">
	<img {src} alt="" />
	<h3 class="blue">{heading}</h3>
	<p>{description}</p>
	<a {href}>Read More &raquo;</a>
</div>

<style>
	div {
		position: relative;
		padding: 2rem;
		font-size: 1.125rem;
		border-radius: 1rem;
	}

	img {
		position: absolute;
		width: 3.5rem;
		top: -1.5rem;
	}

	a {
		display: inline-block;
		font-weight: bold;
	}
</style>
