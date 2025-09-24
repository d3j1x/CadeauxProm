<script lang="ts">
	import Hero from "$lib/components/homeComponents/Hero.svelte";
  import { Alert } from "flowbite-svelte";
</script>

<svelte:head>
	<title>Cadeaux Prom</title>
	<meta
		name="description"
		content="Cadeaux Prom vous accompagne dans la création de cadeaux uniques et personnalisés, parfaits pour anniversaires, mariages, fêtes ou événements d’entreprise."
	/>
</svelte:head>

<div class="m-8">
  <Alert>
    <span class="font-medium">Avis : </span>
    Ce site est actuellement en développement et en cours de création. Merci pour votre patience ! 
  </Alert>
</div>

<Hero />