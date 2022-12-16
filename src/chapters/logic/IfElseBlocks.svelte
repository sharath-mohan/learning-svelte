<script>
	let isOnline = true;
	const toggleStatus = () => {
		isOnline = !isOnline;
	};
</script>

<h2>If Else Block</h2>
<button on:click={toggleStatus}>Toggle</button>
{#if isOnline}
	<p>Server is Online</p>
{:else}
	<p>Server is offline</p>
{/if}
