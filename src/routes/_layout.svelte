<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
	div {
		max-width: 60em;
		margin: auto;
	}
</style>

<div>
	<Nav {segment}/>

	<main>
		<slot></slot>
	</main>
</div>