<script>
	import { fade } from "svelte/transition";
</script>

<div in:fade={{ duration: 200, delay: 200 }} out:fade={{ duration: 200 }}>
	<h1>my projects</h1>
	<p>stuff</p>
</div>
