<script>
	import Nav from './Nav.svelte';
</script>

<svelte:head>
	<title>Taniti</title>
</svelte:head>

<Nav/>

<main>
	<video autoplay muted loop playsinline>
		<source src="/taniti-intro.mp4" type="video/mp4">
		Your browser does not support the video tag.
	</video>
	<div class="video-overlay">
		<h1><a href="/about">Taniti</a></h1>
	</div>
</main>

<style>
	video {
		position: absolute;
		z-index: -1;
		top: calc(-1 * var(--nav-height));
		width: 100%;
		height: 100vh;

		overflow: hidden;
		object-fit: cover;
	}

	.video-overlay {
		position: absolute;
		left: 50%;
		top: 50%;
		padding: 0;

		font-size: 20px;
		border-radius: 16px;
		transform: translate(-50%, -50%) scale(1.0);
		transition: transform 0.3s ease;
	}
	.video-overlay a {
		color: white;
		text-decoration: none;
	}
	.video-overlay:hover {
		transform: translate(-50%, -50%) scale(1.1);
	}
</style>
