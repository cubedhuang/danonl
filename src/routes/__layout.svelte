<script>
	import Nav from "../components/Nav.svelte";
	import { fade } from "svelte/transition";
</script>

<header>
	<Nav />
</header>

<main>
	<slot />
</main>
