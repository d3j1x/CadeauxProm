<script lang="ts">
	import Footer from '$lib/components/layoutComponents/Footer.svelte';
	import Navbar from '$lib/components/layoutComponents/Navbar.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<Navbar />

{@render children()}

<Footer />




