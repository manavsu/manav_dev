<script>
    import "$lib/app.css";
</script>

<style lang="postcss">
	:global(html) {
		@apply text-lg bg-amber-50;
	}

	:global(a) {
		@apply text-teal-500 underline;
	}
</style>

<slot />