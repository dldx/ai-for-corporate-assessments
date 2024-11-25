<script lang="ts">
	import '../styles/app.css'

	let { children } = $props()
</script>

<svelte:head>
	<title>AI for corporate assessments</title>
</svelte:head>

{@render children()}