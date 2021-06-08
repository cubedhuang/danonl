<script>
	import { fly } from "svelte/transition";
</script>

<div in:fly={{ y: 50, duration: 500 }}>
	<h1>my projects</h1>
	<p>stuff</p>
</div>
