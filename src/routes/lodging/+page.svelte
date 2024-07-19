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
	<div class="showcase-content">
		<div class="showcase-container">
			<img src="/lodging/resort.jpg" alt="Taniti Resort">
			<div class="showcase-title">
				<h2>Taniti Resort</h2>
				<p>Resort</p>
				<p>****</p>
				<p>$799/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hostel.jpg" alt="Rijas' Hostel">
			<div class="showcase-title">
				<h2>Rijas' Hostel</h2>
				<p>Hostel</p>
				<p>***</p>
				<p>$449/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hotel1.jpg" alt="Shawman Hotel">
			<div class="showcase-title">
				<h2>Shawman Hotel</h2>
				<p>Hotel</p>
				<p>***</p>
				<p>$529/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/bed-and-breakfast.jpg" alt="Lola's Bed and Breakfast">
			<div class="showcase-title">
				<h2>Lola's Bed and Breakfast</h2>
				<p>Bed and Breakfast</p>
				<p>**</p>
				<p>$249/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home3.jpg" alt="Bay Neighborhood Housing">
			<div class="showcase-title">
				<h2>Bay Neighborhood Housing</h2>
				<p>House</p>
				<p>**</p>
				<p>$214/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home1.jpg" alt="Culpan Family Home">
			<div class="showcase-title">
				<h2>Culpan Family Homes</h2>
				<p>House</p>
				<p>*</p>
				<p>$159/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/hotel2.jpg" alt="Palm Inn">
			<div class="showcase-title">
				<h2>Palm Inn</h2>
				<p>Hotel</p>
				<p>*</p>
				<p>$149/night</p>
			</div>
		</div>
		<div class="showcase-container">
			<img src="/lodging/home2.jpg" alt="Volcanic Outlook Houses">
			<div class="showcase-title">
				<h2>Volcanic Outlook Houses</h2>
				<p>House</p>
				<p>*</p>
				<p>$124/night</p>
			</div>
		</div>
	</div>
</main>

<Footer />
