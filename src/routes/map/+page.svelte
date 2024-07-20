<script>
	import Nav from '../Nav.svelte';
</script>

<svelte:head>
	<title>Map of Taniti</title>
</svelte:head>

<Nav />

<main>
	<img src="/map/taniti.svg" alt="Taniti Island Map">
</main>

<style>
	main {
		position: absolute;
		top: 0;
		height: 100%;

		background-color: skyblue;
	}
</style>
