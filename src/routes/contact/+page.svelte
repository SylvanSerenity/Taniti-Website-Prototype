<script>
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';
</script>

<svelte:head>
	<title>Contact</title>
</svelte:head>

<Nav />

<main>
	<h1>Contact Us</h1>
	<form>
		<label>
			Email:
			<input type="text" placeholder="email@domain.ext" required />
		</label>
		<label>
			Subject:
			<input type="text" placeholder="Subject" required />
		</label>
		<label>
			Message:
			<textarea placeholder="Message..." required></textarea>
		</label>
		<button type="submit">Send</button>
	</form>
</main>

<Footer />
