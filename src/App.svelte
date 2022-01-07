<script>
	import { routes, Router } from 'svelte-hash-router';
	import Footer from "./Footer.svelte";
	import Header from "./Header.svelte";
	import Home from "./Home.svelte";
	import Price from "./Price.svelte";
	import Ftrs from "./Ftrs.svelte";
	import Inspri from "./Inspri.svelte";
	routes.set({
		'/':Home,
		'/ftrs':Ftrs,
		'/price':Price,
		'/inspri':Inspri,
	})
</script>

<main>
	<Header/>
	<Footer/>
</main>
<style>
</style>