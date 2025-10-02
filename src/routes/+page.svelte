<script lang="ts">
	import Hero from "$lib/components/homeComponents/Hero.svelte";
	import Secondary from "$lib/components/homeComponents/Secondary.svelte";
  import { Alert } from "flowbite-svelte";
</script>

<svelte:head>
	<title>Cadeaux Prom</title>
	<meta
		name="description"
		content="Cadeaux Prom vous accompagne dans la création de cadeaux uniques et personnalisés, parfaits pour anniversaires, mariages, fêtes ou événements d’entreprise."
	/>
</svelte:head>


  <Alert class="rounded-none m-0 p-1 text-center">
    <span class="font-medium">Avis : Ce site est actuellement en développement et en cours de création.</span>
    <span class="font-bold">Merci pour votre patience !</span> 
  </Alert>


<Hero />

<Secondary />