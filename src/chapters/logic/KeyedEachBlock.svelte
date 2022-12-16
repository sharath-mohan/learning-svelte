<script>
	const fruits = ['apples', 'grapes', 'lemons'];
</script>

<h2>Keyed Each Block</h2>
<ul>
	{#each fruits as fruit, index (fruit)}
		<li>{index + 1}. {fruit}</li>
	{/each}
</ul>
