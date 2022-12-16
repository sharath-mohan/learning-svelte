<script>
	import { createEventDispatcher } from 'svelte';
	const dispatch = createEventDispatcher();
	const childEvent = () => {
		dispatch('message', {
			data: 'hello'
		});
	};
</script>

<h2>Child Element</h2>
<button on:click={childEvent}>Click to Emit Event</button>
