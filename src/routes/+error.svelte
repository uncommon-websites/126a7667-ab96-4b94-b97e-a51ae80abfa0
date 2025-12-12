<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen flex items-center justify-center bg-cream px-4">
	<div class="text-center">
		<h1 class="text-6xl font-serif mb-4">Error {page.status}</h1>
		<p class="text-xl text-gray-600 mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium bg-dark text-white hover:bg-gray-800 transition-transform active:scale-95">
			Go back home
		</a>
	</div>
</main>
