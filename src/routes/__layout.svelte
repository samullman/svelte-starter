<script>
	import Header from '../components/header.svelte';
	import '../app.css';
</script>

<Header />

<main>
	<div>
		<slot />
	</div>
</main>

<footer>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</footer>

<style lang="scss">
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		width: 100%;
		padding: 0 1rem;
		max-width: 52rem;
		margin: 0 auto;
		margin-top: 3.25rem;
		min-height: 32rem;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		max-width: 52rem;
		padding: 1rem;
		margin: 0 auto;
	}
</style>
