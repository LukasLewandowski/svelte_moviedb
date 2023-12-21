<script>
	let count = 0;

	function incrementBtn() {
		count += 1;
	}
</script>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
</nav>

<h1>Number: {count}</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={incrementBtn}> Increment </button>

<style>
	button {
		background-color: rgb(147, 161, 201);
	}
</style>
