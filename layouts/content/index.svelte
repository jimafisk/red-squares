<script>
	export let title;

  import Squares from '../components/squares.svelte';
</script>

<h1>{title}</h1>

<Squares />

<style>
	h1 {
		font-family: Helvetica, sans-serif;
	}
</style>
