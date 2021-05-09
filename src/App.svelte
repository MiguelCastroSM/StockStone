<script>
	export let name;
	import CustomButton from './CustomButton.svelte';

function handleClick() {
	alert('clicked');
}
</script>

<main>
	<h1> Stone Control Stock</h1>
	
	<CustomButton nombre="Controlar Stock" on:click={handleClick}/>
	<CustomButton nombre="Agregar Stock" on:click={handleClick}/>
	<CustomButton nombre="Quitar  &nbsp;Stock &nbsp;" on:click={handleClick}/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: whitesmoke;
	}

	h1 {
		color: #44b6ac;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>