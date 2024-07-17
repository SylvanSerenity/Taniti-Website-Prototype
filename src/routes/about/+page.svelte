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
	<Slideshow {slides} />
</main>
