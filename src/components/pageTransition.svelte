<script lang="ts">
	import { fade } from 'svelte/transition';
	export let refresh: URL;
</script>

{#key refresh}
	<div in:fade out:fade>
		<slot />
	</div>
{/key}
