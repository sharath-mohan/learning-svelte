<script>
	let x = 0;
	let y = 0;
</script>

<h2>Inline events</h2>
<div
	class="container"
	on:mousemove={(e) => {
		x = e.clientX;
		y = e.clientY;
	}}
>
	<p>{x},{y}</p>
</div>

<style>
	.container {
		background-color: lemonchiffon;
		border: 1px solid;
		padding: 2rem;
		margin: 1rem;
	}
</style>
