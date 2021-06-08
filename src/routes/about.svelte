<script>
	import { fade } from "svelte/transition";
</script>

<svelte:head>
	<title>about</title>
</svelte:head>

<div in:fade={{ duration: 200, delay: 200 }} out:fade={{ duration: 200 }}>
	<h1>about</h1>
</div>
