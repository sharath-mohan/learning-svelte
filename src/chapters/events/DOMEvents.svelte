<script>
	let x = 0;
	let y = 0;
	const mousemoveEventHander = (event) => {
		x = event.clientX;
		y = event.clientY;
	};
</script>

<h2>DOM events</h2>
<div class="container" on:mousemove={mousemoveEventHander}>
	<p>{x},{y}</p>
</div>

<style>
	.container {
		background-color: #ccc;
		border: 1px solid;
		padding: 2rem;
		margin: 1rem;
	}
</style>
