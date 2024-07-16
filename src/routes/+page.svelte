<script>
	import Nav from 'Nav.svelte';
</script>

<Nav/>

<main>
	<video autoplay muted loop playsinline>
		<source src="/taniti.mp4" type="video/mp4">
		Your browser does not support the video tag.
	</video>
</main>

<style>
	video {
		position: absolute;
		z-index: -1;
		top: 0;
		width: 100%;
		height: 100%;

		overflow: hidden;
		object-fit: cover;
	}
</style>

