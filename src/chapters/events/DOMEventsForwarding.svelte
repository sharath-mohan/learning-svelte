<script>
	import CustomButton from './CustomButton.svelte';
	const logger = () => {
		console.log('custom button event');
	};
</script>

<h2>DOM events forwarding</h2>
<CustomButton on:click={logger} />
