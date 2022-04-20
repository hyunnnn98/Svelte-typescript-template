<script lang="ts">
	export let name: string;
</script>

<main class="container mx-auto p-3 text-center">
	<h1 class="text-4xl font-bold uppercase text-svelte-color">{name}</h1>
	<p class="p-6 hover:font-bold">
		Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
		how to build Svelte appsa.
	</p>
</main>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
