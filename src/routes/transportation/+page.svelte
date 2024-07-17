<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
</script>

<svelte:head>
	<title>Transportation</title>
</svelte:head>

<Nav />

<main>
	<h1>Transportation</h1>
	<div class="split-content">
		<div class="text-container">
			<h2>Arrival & Departure</h2>
			<p>You can arrive by plane!</p>
			<p>You can depart by cruise!</p>
		</div>
		<div class="text-container">
			<h2>Ground Transportation</h2>
			<p>You can travel by car!</p>
		</div>
	</div>
</main>

<Footer />
