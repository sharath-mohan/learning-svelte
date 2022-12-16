<script>
	let isOnline = true;
	const toggleStatus = () => {
		isOnline = !isOnline;
	};
</script>

<h2>If Block</h2>
<button on:click={toggleStatus}>Toggle</button>
{#if isOnline}
	<p>Server is Online</p>
{/if}
