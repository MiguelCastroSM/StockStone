<script>
	
	import CustomButton from './CustomButton.svelte';

function handleClick() {
	alert('clicked');
}
</script>

<main>
	<img style="text-align: left;" src="logo.jpg" alt="logo">

	<h1> Stone Control Stock</h1>
	<center>
	<CustomButton nombre="Controlar Stock" on:click={handleClick}/>
	<CustomButton nombre="Agregar Stock" on:click={handleClick}/>
	<CustomButton nombre="Quitar  &nbsp;Stock &nbsp;" on:click={handleClick}/>
	</center>
</main>

<style>
	main {
		
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background-color: white;
	}

	h1 {
		text-align: center;
		color: #44b6ac;
		text-transform: uppercase;
		font-size: 350%;
		
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>