<script>
	const showAlert = () => {
		alert('I will be displayed only once');
	};
</script>

<h2>Event Modifiers</h2>
<button on:click|once={showAlert}>show aler only once</button>
