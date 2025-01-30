<script lang="ts">
	import Footer from '../lib/components/Footer.svelte';

	import NavBar from '../lib/components/NavBar.svelte';

	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<title>Positivus</title>
	<link rel="icon" href="favicon.png" type="image/png" />

	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Positivus" />
	<meta
		property="og:description"
		content="A stunning and versatile SvelteKit Landing Page designed for digital marketing agencies."
	/>
	<meta property="og:image" content="/link-thumbnail.jpeg" />

	<!-- Twitter -->
	<meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:title" content="Positivus" />
	<meta
		name="twitter:description"
		content="A stunning and versatile SvelteKit Landing Page designed for digital marketing agencies."
	/>
	<meta name="twitter:image" content="/link-thumbnail.jpeg" />
</svelte:head>
<NavBar />
{@render children()}
<Footer />

<style>
	.space-grotesk-300 {
		font-family: 'Space Grotesk', serif;
		font-optical-sizing: auto;
		font-weight: 300;
		font-style: normal;
	}

	.space-grotesk-400 {
		font-family: 'Space Grotesk', serif;
		font-optical-sizing: auto;
		font-weight: 400;
		font-style: normal;
	}

	.space-grotesk-500 {
		font-family: 'Space Grotesk', serif;
		font-optical-sizing: auto;
		font-weight: 500;
		font-style: normal;
	}

	.space-grotesk-600 {
		font-family: 'Space Grotesk', serif;
		font-optical-sizing: auto;
		font-weight: 600;
		font-style: normal;
	}

	.space-grotesk-700 {
		font-family: 'Space Grotesk', serif;
		font-optical-sizing: auto;
		font-weight: 700;
		font-style: normal;
	}
</style>
