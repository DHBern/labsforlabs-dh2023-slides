<script lang="ts">
	import { dev } from '$app/environment';

	import Markdown from './markdown.svelte'
</script>

<Markdown name="{ dev ? 'slides.md' : 'labsforlabs-dh2023-slides/slides.md'}" external />