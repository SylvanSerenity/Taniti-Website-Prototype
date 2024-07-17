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

<main>
	<h1>About</h1>
	<div class="slideshow-container">
		<Slideshow {slides} />
	</div>
</main>

<style>
	.slideshow-container {
		width: 75%;
		height: 75%;
	}
</style>
