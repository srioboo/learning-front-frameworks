<script lang="ts">
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<div>
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	/**
		Estilos del layout
	*/
</style>
