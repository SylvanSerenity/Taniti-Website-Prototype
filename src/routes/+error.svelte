<script>
	import { page } from '$app/stores';
	import Nav from './Nav.svelte';
	import Footer from './Footer.svelte';
</script>

<svelte:head>
	<title>Error</title>
</svelte:head>

<Nav />

<main>
	<h1>Something went wrong...</h1>
	<p>{$page.status ? $page.status + ': ' : ''}{$page.error? $page.error.message : 'An unknown error occurred.'}</p>
	<a href="/">Home</a>
</main>

<Footer />

<style>
	a {
		text-align: center;
		background-color: skyblue;
		padding: 8px;
		border-radius: 10px;
		color: white;
		text-decoration: none;
		box-shadow: 2px 2px 5px 0px rgba(0, 0, 0, 0.2);
	}
</style>
    
