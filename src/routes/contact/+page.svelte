<script>
	import Form from '../../lib/Form.svelte'
	import Title from '../../lib/Title.svelte'
</script>

<svelte:head>
	<title>Contact - Acme Website</title>
</svelte:head>

<Title name="Contact" />

<section>
	<div class="outer">
		<div class="inner flow">
			<h2>Send us a message</h2>
			<div class="form-container">
				<Form />
			</div>
		</div>
	</div>
</section>

<style>
	.form-container {
		max-width: 48rem;
	}
</style>
