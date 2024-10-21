<script>
	import Title from '$lib/Title.svelte'

	export let data
</script>

<Title name={data.post.title} />

<section>
	<div class="outer">
		<div class="inner">
			<div>
				<img src={data.post.featured_image} alt="" />
			</div>
		</div>
	</div>
</section>
