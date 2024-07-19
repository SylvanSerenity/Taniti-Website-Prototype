<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
</script>

<svelte:head>
	<title>Entertainment</title>
</svelte:head>

<Nav />

<main>
	<h1>Entertainment</h1>
	<div class="stacked-content">
		<div class="stacked-item">
			<img src="/entertainment/ziplining.jpg" alt="Ziplining">
			<div class="text-container">
				<h2>Ziplining</h2>
				<p>
					Taniti offers two ziplining adventures to take you high above some the island's most stunning locations!
					One decends a mountainous rainforest with many blue holes, and the other takes you from the side of the
					volcano to the nearby rocky beaches!
				</p>
			</div>
		</div>
		<div class="stacked-item">
			<!-- TODO -->
		</div>
	</div>
</main>

<Footer />
