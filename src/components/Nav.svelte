<nav>
	<a href="." class="name">
		<img src="/wireframe.svg" alt="logo" height="20" width="20" />
	</a>
	<a href="about">about</a>
	<a href="projects">projects</a>
</nav>

<style>
	nav {
		width: 100%;
		display: flex;
		align-items: center;
		padding: 8em 0 4em 0;
	}

	.name {
		margin-right: auto;
	}

	.name img {
		width: 3em;
		height: auto;
	}

	a {
		color: white;
		transition-property: border, filter;
		transition-duration: 0.2s;
	}

	a:hover {
		filter: drop-shadow(0 0 0.5em #fff);
	}

	a:not(.name) {
		text-decoration: none;
		border-bottom: 1px solid white;
		padding: 1px 0;
	}

	a:not(.name):hover {
		border-bottom: 1px solid transparent;
	}

	a:nth-child(n + 3) {
		margin-left: 1em;
	}
</style>
