<button on:click>
	{nombre}
</button>

<script>
	// your script goes here
	export let nombre={nombre};
</script>

<style>
	button {
		text-align: center;
		height: auto;
		width: 30%;
		background-color:#44b6ac;
		border-color: #555;
		color: #555;
		font-size: 1.25rem;
		background-image: linear-gradient(45deg, #555 50%, transparent 50%);
		background-position: 100%;
		background-size: 400%;
		transition: background 600ms ease-in-out;
	}
	button:hover {
		background-position: 0;
		color: #44b6ac;
	}
</style>