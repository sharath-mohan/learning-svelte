<script>
	import ComponentEventsChild from './ComponentEventsChild.svelte';
	const onMessage = (event) => {
		console.log(event.detail);
	};
</script>

<ComponentEventsChild on:message={onMessage} />
