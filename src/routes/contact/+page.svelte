<script lang="ts">
	import Nav from '../Nav.svelte';
	import Footer from '../Footer.svelte';

	let email = '';
	let subject = '';
	let message = '';

	function sendForm(event: SubmitEvent) {
		event.preventDefault();

		alert("Sent!");
		email = '';
		subject = '';
		message = '';
	}
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
			<input bind:value={email} type="text" placeholder="email@domain.ext" required />
		</label>
		<label>
			Subject:
			<input bind:value={subject} type="text" placeholder="Subject" required />
		</label>
		<label>
			Message:
			<textarea bind:value={message} placeholder="Message..." required></textarea>
		</label>
		<button type="submit" onsubmit={sendForm}>Send</button>
	</form>
</main>

<Footer />
