<script>
	let value = 0;
	$: doubled = value * 2;
	const increment = () => {
		++value;
	};
</script>

<h2>Declarations</h2>
<button on:click={increment}>increment</button>
<p>Counter {value} * 2 = {doubled}</p>
