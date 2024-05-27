<script lang="ts">
	export let title = "ErrorTek's blog";

	export let heroImage = "";

	export let description = "ErrorTek's website";

	export let imageHost = "";

	export let imageProtocol = "";
</script>

<svelte:head>
	<title>{title}</title>
	<meta content={title} name="og:title" />
	<meta content={title} name="twitter:title" />
	{#if heroImage && imageHost && imageProtocol}
		<meta
			content="{imageProtocol}//{imageHost}{heroImage}"
			name="og:image"
		/>
		<meta
			content="{imageProtocol}//{imageHost}{heroImage}"
			name="twitter:image"
		/>
		<meta content="summary_large_image" name="twitter:card" />
	{:else}
		<meta content="summary" name="twitter:card" />
		<meta content="https://avatars.githubusercontent.com/jpbandroid" name="twitter:image" />
		<meta content="https://avatars.githubusercontent.com/jpbandroid" name="og:image" />
	{/if}
	<meta content={description} name="description" />
	<meta content={description} name="og:description" />
	<meta content={description} name="twitter:description" />
</svelte:head>
