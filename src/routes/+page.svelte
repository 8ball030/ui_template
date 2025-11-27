<!-- We add in the background and center everything -->
<script lang="ts">
	import { Button } from '$lib/components/ui/button/index.js';
	let count = 0;
</script>

<main class="flex min-h-screen flex-col items-center justify-center bg-primary p-4 text-primary-foreground">
	<h1>Welcome to SvelteKit</h1>
	<p>
		Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation
	</p>

	<p class="mt-4">Count: {count}</p>

	<Button onclick={() => count++} variant="secondary">Increment</Button>
</main>
