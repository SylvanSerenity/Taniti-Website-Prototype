<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
	import Slideshow from './Slideshow.svelte';

	const slides = [
		{src: '/slideshow/volcano.jpg', text: 'Visit our active volcano!'}
	];
</script>

<svelte:head>
	<title>About Taniti</title>
</svelte:head>

<Nav />

<main>
	<h1>About</h1>
	<div class="slideshow-container">
		<Slideshow {slides} />
	</div>
</main>

<Footer />

<style>
	.slideshow-container {
		width: 60vw;
		height: 60vh;
		background-color: rgba(0, 0, 0, 0.2);
		overflow: hidden;
	}
</style>
