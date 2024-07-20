<script>
	import Nav from '../Nav.svelte';
	import Map from './Map.svelte';
</script>

<svelte:head>
	<title>Map of Taniti</title>
</svelte:head>

<Nav />

<main>
	<Map />
</main>

<style>
	main {
		position: absolute;
		top: 0;
		height: 100%;

		background-color: skyblue;
	}
</style>
