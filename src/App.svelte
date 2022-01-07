<script>
	import { routes, Router } from 'svelte-hash-router';
	import Footer from "./Footer.svelte";
	import Header from "./Header.svelte";
	import Home from "./Home.svelte";
	import Price from "./Price.svelte";
	import Ftrs from "./Ftrs.svelte";
	import Inspri from "./Inspri.svelte";
	import Video1 from "./Video1.svelte";
	import Video2 from "./Video2.svelte";
	import Video3 from "./Video3.svelte";
	import Video4 from "./Video4.svelte";
	// import Video5 from './Video5.svelte';
	import Video6 from "./Video6.svelte";
	import Video7 from "./Video7.svelte";
	import Video8 from "./Video8.svelte";
	routes.set({
		'/':Home,
		'/ftrs':Ftrs,
		'/price':Price,
		'/inspri':{$$component:Inspri,
			'/video1':Video1,
			'/video2':Video2,
			'/video3':Video3,
			'/video4':Video4,
			// '/video5':Video5,
			'/video6':Video6,
			'/video7':Video7,
			'/video8':Video8}
	})
</script>
<main>
	<Header/>
	<Footer/>
</main>
<style>
</style>