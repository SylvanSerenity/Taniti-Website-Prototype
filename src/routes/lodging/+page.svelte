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
			<img src="/lodging/resort.jpg" alt="Taniti Resort">
			<h2>Taniti Resort</h2>
			<p>Resort</p>
			<p>****</p>
			<p>$799/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hostel.jpg" alt="Rijas' Hostel">
			<h2>Rijas' Hostel</h2>
			<p>Hostel</p>
			<p>***</p>
			<p>$449/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hotel1.jpg" alt="Shawman Hotel">
			<h2>Shawman Hotel</h2>
			<p>Hotel</p>
			<p>***</p>
			<p>$529/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hotel2.jpg" alt="Palm Inn">
			<h2>Palm Inn</h2>
			<p>Hotel</p>
			<p>*</p>
			<p>$149/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home1.jpg" alt="Culpan Family Home">
			<h2>Culpan Family Homes</h2>
			<p>House</p>
			<p>*</p>
			<p>$159/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home2.jpg" alt="Blue Hole Houses">
			<h2>Blue Hole Houses</h2>
			<p>House</p>
			<p>*</p>
			<p>$124/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home3.jpg" alt="Yellow Leaf Bay Neighborhood Housing">
			<h2>Yellow Leaf Bay Neighborhood Housing</h2>
			<p>House</p>
			<p>**</p>
			<p>$214/night</p>
		</div>
		<div class="showcase-container">
			<img src="/lodging/bed-and-breakfast.jpg" alt="Lola's Bed and Breakfast">
			<h2>Lola's Bed and Breakfast</h2>
			<p>House</p>
			<p>**</p>
			<p>$249/night</p>
		</div>
	</div>
</main>

<Footer />
