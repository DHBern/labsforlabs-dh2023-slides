<script lang="ts">
	export let name = 'example.md'
	export let external = false
</script>

{#if external}
	<section data-markdown={name} data-separator-vertical="^::" />
{:else}
	<section data-markdown>
		<div data-template>
			<slot />
		</div>
	</section>
{/if}
