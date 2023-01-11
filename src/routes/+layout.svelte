<script>
	import Header from './Header.svelte';
	import './styles.css';
	import "../app.css";
</script>

<div class="app">
	<Header />

	<main>
		<h1 class="text-3xl font-bold underline">
			Hello world!
		</h1>
		<slot />
	</main>

	<footer>
		footer
	</footer>
</div>

<style>

</style>
