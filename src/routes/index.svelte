<h1>Welcome to SvelteKit</h1>
<p>Visit <a href='https://kit.svelte.dev'>kit.svelte.dev</a> to read the documentation</p>

<p>{counter}</p>
<button on:click={(event) => {
	console.log(event);
	counter += 1;
}}>incrementar
</button>

<a href='/about'>bdsyu</a>

<script>
	let counter = 0;
</script>

<style>
	p { color: red; }
</style>
