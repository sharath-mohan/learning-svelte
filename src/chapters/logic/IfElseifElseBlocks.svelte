<script>
	const status = ['online', 'offline', 'vanished'];
	let serverStatus = status[0];
	const toggle = () => {
		const index = Math.round(Math.random() * 2);
		console.log(index);

		serverStatus = status[index];
	};
</script>

<h2>If Else if else block</h2>
<button on:click={toggle}>toggle</button>
<p>The server is</p>
{#if serverStatus === 'online'}
	<p>running awesome</p>
{:else if serverStatus == 'offline'}
	<p>gone offline</p>
{:else}
	<p>vanished into cyber black hole</p>
{/if}
