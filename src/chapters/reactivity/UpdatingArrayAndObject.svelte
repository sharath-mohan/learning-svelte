<script>
	let list = [];
	const addRandom = () => {
		list = [...list, Math.round(Math.random() * 10)];
	};
	let server = {
		name: 'Friday',
		status: 'online'
	};
	const toggleStatus = () => {
		server = { ...server, status: server.status === 'online' ? 'offline' : 'online' };
	};
</script>

<h2>Updating arrays and Object</h2>
<button on:click={addRandom}>Add Random</button>
<p>{JSON.stringify(list)}</p>
<p>{server.name} - {server.status}</p>
<button on:click={toggleStatus}>toggle status</button>
