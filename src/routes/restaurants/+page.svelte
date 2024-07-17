<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
</script>

<svelte:head>
	<title>Restaurants</title>
</svelte:head>

<Nav />

<main>
	<h1>Restaurants</h1>
	<div class="stacked-content">
		<div class="stacked-item">
			<img src="/restaurants/volcanic-cafe.jpg" alt="Volcanic Cafe">
			<div class="text-container">
				<h2>Volcanic Cafe</h2>
				<p>Enjoy a local buffet at this volcanic-themed cafe!</p>
			</div>
		</div>
		<div class="stacked-item">
			<img src="/restaurants/bay-grill.jpg" alt="Yellow Leaf Bay Grill">
			<div class="text-container">
				<h2>Yellow Leaf Bay Grill</h2>
				<p>This American-style restuarant has </p>
			</div>
		</div>
	</div>
</main>

<Footer />
