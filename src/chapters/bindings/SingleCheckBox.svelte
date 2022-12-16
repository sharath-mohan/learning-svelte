<script>
	let agree = false;
</script>

<h2>Single Checkbox</h2>
<label for="agree"> I agree to terms of service </label>
<input type="checkbox" bind:checked={agree} id="agree" />
{#if agree}
	Great that you agree
{:else}
	aww! thats to bad
{/if}
