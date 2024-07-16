<script>
	import Nav from './Nav.svelte';
</script>

<Nav/>

<main>
	<video autoplay muted loop playsinline>
		<source src="/taniti.mp4" type="video/mp4">
		Your browser does not support the video tag.
	</video>
	<div class="video-overlay">
		<h1><a href="/about">About</a></h1>
	</div>
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

	.video-overlay {
		position: absolute;
		left: 50%;
		top: 50%;
		padding: 15px;

		background-color: #00800025;
		font-size: 20px;
		border-radius: 16px;
		transform: translate(-50%, -50%) scale(1.0);
		transition: transform 0.3s ease, background-color 0.3s ease;
	}
	.video-overlay a {
		color: white;
		text-decoration: none;
	}
	.video-overlay:hover {
		background-color: #00800055;
		transform: translate(-50%, -50%) scale(1.1);
	}
</style>
