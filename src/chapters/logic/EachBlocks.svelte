<script>
	const fruits = ['apples', 'grapes', 'lemons'];
</script>

<h2>Each Block</h2>
<ul>
	{#each fruits as fruit, index}
		<li>{index + 1}. {fruit}</li>
	{/each}
</ul>
