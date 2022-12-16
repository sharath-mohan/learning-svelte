<script>
	let users = [];
	import { onMount } from 'svelte';
	const fetchUsers = async () => {
		const res = await fetch('https://jsonplaceholder.typicode.com/users');
		const data = await res.json();
		users = [...data];
	};
	onMount(fetchUsers);
</script>

<h2>On Mount</h2>
<ul>
	{#each users as user (user.id)}
		<li>{user.name}</li>
	{/each}
</ul>
