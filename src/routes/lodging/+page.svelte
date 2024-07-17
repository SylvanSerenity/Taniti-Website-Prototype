<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
</script>

<svelte:head>
	<title>Lodging</title>
</svelte:head>

<Nav />

<main>
	<h1>Lodging</h1>
	<div class="split-content">
		<div class="showcase-container">
			<img src="/lodging/taniti-resort.jpg" alt="Taniti Resort">
			<h2>Taniti Resort</h2>
			<p>Resort</p>
			<p>****</p>
			<p>$799/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/palm-inn.jpg" alt="Palm Inn">
			<h2>Palm Inn</h2>
			<p>Hotel</p>
			<p>***</p>
			<p>$529/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/shawman-hotel.jpg alt="Shawman Hotel">
			<h2>Shawman Hotel</h2>
			<p>Hotel</p>
			<p>***</p>
			<p>$449/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/rijas-hostel.jpg" alt="Rijas' Hostel">
			<h2>Rijas' Hostel</h2>
			<p>Hostel</p>
			<p>*</p>
			<p>$179/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/culpan-home.jpg" alt="Culpan Family Home">
			<h2>Culpan Family Home</h2>
			<p>Hostel</p>
			<p>*</p>
			<p>$159/night</p>
		</div>
	</div>
</main>

<Footer />
