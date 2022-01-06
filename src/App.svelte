<script>
	import Footer from "./Footer.svelte";
	import Header from "./Header.svelte";
	import Home from "./Home.svelte";
	import Price from "./Price.svelte";
	import Ftrs from "./Ftrs.svelte";
	import Inspri from "./Inspri.svelte";
	import { Router, Route, Link } from "svelte-navigator";
</script>

<main>
	<Router>
	<Header/>
	<Route path="/" component={Home} />
	<Route path="ftrs" component={Ftrs} />
	<Route path="price" component={Price} />
	<Route path="inspri" component={Inspri} />
	<Footer/>
	</Router>
</main>
<style>
</style>