<script>	
	import { page } from '$app/stores';	
	console.log(page)
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	{$page.params.id}
</section>

<style>

</style>
