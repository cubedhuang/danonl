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

	a.name {
		margin-right: auto;
	}

	.name img {
		width: 3em;
		height: auto;
	}

	a {
		color: white;
		transition-property: border, opacity;
		transition-duration: 0.2s;
	}

	a:hover {
		opacity: 0.8;
	}

	a:not(.name) {
		text-decoration: none;
		border-bottom: 1px solid white;
	}

	a:not(.name):hover {
		border-bottom: 1px solid transparent;
	}

	a:nth-child(n + 3) {
		margin-left: 2em;
	}
</style>
