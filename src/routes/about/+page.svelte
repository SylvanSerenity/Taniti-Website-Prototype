<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
	import Slideshow from './Slideshow.svelte';

	const slides = [
		{src: '/slideshow/volcano.jpg', text: 'Taniti\'s active volcano, Mt. Phosphur, is the longest-active volcano in the world!'}
	];
</script>

<svelte:head>
	<title>About Taniti</title>
</svelte:head>

<Nav />

<main>
	<h1>About</h1>
	<div class="slideshow-container">
		<Slideshow {slides} />
	</div>
	<h1>Frequently Asked Questions</h1>
	<div class="single-content">
		<div class="text-container">
			<h2>Which language is spoken on the island?</h2>
			<p>The official language of Taniti is Malaysian, but much of the younger generations speak fluent English as well. English is less often spoken in rural areas or by the older population.</p>
			<h2>Which currency is used on the island?</h2>
			<p>Taniti uses the United States Dollar currency. Many places accept debit and credit, but there are multiple ATMs on the island if you need cash.</p>
			<h2>Do I need to bring outlet adapters?</h2>
			<p>No need! Taniti uses 120-volt outlets like you'd find in the United States; however, most lodging options are equipped with transformers for 240-volt appliances and have adapters for European outlets.</p>
			<h2>Are there any medical facilities?</h2>
			<p>Taniti has one hospital with multilingual employees and several small clinics spread across the island.</p>
			<h2>Does Taniti have holidays?</h2>
			<p>Taniti celebrates many national holidays, some of which you may have the pleasure to experience on your trip. Many tourist attractions and facilities will be closed on holidays, so please plan accordingly.</p>
			<h2>Is alcohol served?</h2>
			<p>Yes, but is only served until midnight. Please do not drink publicly between the hours of midnight and 09:00.</p>
			<h2>What is the drinking age?</h2>
			<p>Though not strictly enforced, the legal drinking age in Taniti is 18 years old. Please do not allow anyone under 18 to drink in public.</p>
			<h2>Should I be concerned about crime?</h2>
			<p>Taniti fosters a very safe and friendly community. Crime is extraordinarily rare on the island, but as tourism increases, there have been reports of petty crimes such as pickpocketing.</p>
		</div>
	</div>
</main>

<Footer />

<style>
	.slideshow-container {
		width: 80%;
		height: 75vh;
		background-color: rgba(0, 0, 0, 0.2);
		overflow: hidden;
	}
</style>
