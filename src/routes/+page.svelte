<script>
	import Box from '../lib/Box.svelte'
	import HeadingBox from '../lib/HeadingBox.svelte'
	import Hero from '../lib/Hero.svelte'
</script>

<svelte:head>
	<title>Home - Articles about Stuff - Acme Website</title>
	<meta
		name="description"
		content="The Acme Website is the home of so many great things. ..."
	/>
</svelte:head>

<Hero />

<section>
	<div class="outer bg-gradient-gray">
		<div class="inner auto-fit">
			<HeadingBox heading="Check out our most popular categories!" />
			<Box heading="Animation" src="/icons/icon-animation.svg" />
			<Box heading="Business" src="/icons/icon-business.svg" />
			<Box heading="Design" src="/icons/icon-design.svg" />
			<Box heading="Photography" src="/icons/icon-photography.svg" />
			<Box heading="Programming" src="/icons/icon-programming.svg" />
		</div>
	</div>
</section>

<style>
	.inner {
		padding-block: 8rem;
	}
</style>
