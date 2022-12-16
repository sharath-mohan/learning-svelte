<script>
	const frameworks = ['Angular', 'React', 'Vue', 'Svelte'];
	let selected = frameworks[1];
</script>

<h2>Select Binding</h2>
<select bind:value={selected} on:change={() => console.log(selected)}>
	{#each frameworks as framework}
		<option value={framework}>{framework}</option>
	{/each}
</select>
