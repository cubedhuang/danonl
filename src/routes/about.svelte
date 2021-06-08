<script>
	import { fly } from "svelte/transition";
</script>

<svelte:head>
	<title>about</title>
</svelte:head>

<div in:fly={{ y: 50, duration: 500 }}>
	<h1>about</h1>
</div>
