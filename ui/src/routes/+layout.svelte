<script lang="ts">
	import '../app.pcss';
	import '@fontsource-variable/plus-jakarta-sans';
	import Navbar from '$lib/components/Navbar.svelte';
</script>

<Navbar />
<main class="px-2 py-2.5 sm:px-4">
	<div class="container mx-auto mt-5">
		<slot />
	</div>
</main>
