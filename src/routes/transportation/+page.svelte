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
			<p>
				Most visitors to Taniti travel to and from the island by air. There is a small airport that
				accommodates small jets and propeller planes, and offers flights to and from the country. The
				airport is being expanded so it can land larger commercial aircraft, and is expected to handle
				commercial flights within the next few years.
			</p>
			<p>
				If you prefer to travel by land, a small cruise ship travels to and from the mainland every
				Friday night. You will arrive in or depart from Yellow Leaf Bay after travelling around the
				island's north-eastern perimeter. Depending on swells, the cruise ship may take the longer
				route around the south-western perimeter.
			</p>
			<p>
				Please be aware that all methods of getting to and from the island may be cancelled due to
				weather. You will be offered to reschedule via air or sea, or a full refund.
			</p>
		</div>
		<div class="text-container">
			<h2>Ground Transportation</h2>
			<p>
				The best option to get around Taniti City is the free public transportation service, which runs
				from 05:00 to 23:00 every day. Private buses serve the rest of the island for a small fee. Taxis
				are also available in the city, and rental cars are available from the local rental agency near
				the airport.
			</p>
			<p>
				Bikes are also a common mode of transportation, especially in rural areas. Bikes and helmets are
				available for rent from several vendors both inside and outside of Taniti City. Please note that
				helmets are required by law across the entire island. Another common option is walking, as Taniti
				City is fairly flat and has great pedestrian infrastructure. The surrounding Merriton Landing is
				also easy to explore on foot.
			</p>
		</div>
	</div>
</main>

<Footer />

<style>
	h2 {
		text-align: center;
	}
</style>
