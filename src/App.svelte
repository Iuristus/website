<script lang="ts">
	export let name: string;
</script>

<main>
	<h1>{name}</h1>
	<img src="./favicon.png" alt="Iuristus logo" />
	<p>We are currently building the website, come back later to see how we try to improve  Open Source projects !</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	img {
		max-width: 230px;
	}
	h1 {
		color: #928a3c;
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