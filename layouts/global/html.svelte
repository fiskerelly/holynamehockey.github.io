<script>
	import Head from "./head.svelte";
	export let content, layout, env;
</script>

<html lang="en">
	<Head />
	<body>
		<nav>
			<img src="/logo.webp" alt="Holy Name Hockey Golf Tournament" />
		</nav>
		<svelte:component this={layout} {...content.fields} />
	</body>
</html>
