<script>
	let value = 0;
	const increment = () => {
		++value;
	};
</script>

<h2>Statements</h2>
<button on:click={increment}>increment</button>
<p>Counter {value}</p>
