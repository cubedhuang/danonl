<script>
	import Nav from "../components/Nav.svelte";
	import { fly } from "svelte/transition";
</script>

<header>
	<Nav />
</header>

<main>
	<slot />
</main>
