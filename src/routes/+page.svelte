<script>
	import ContactUs from './ContactUs.svelte';

	import TheTeam from './TheTeam.svelte';
	import WorkingProcess from './WorkingProcess.svelte';
	import CastStudies from './CastStudies.svelte';
	import CTA from '../lib/components/CTA.svelte';
	import Services from '../lib/components/Services.svelte';
	import CustomerLogos from '../lib/components/CustomerLogos.svelte';
	import Hero from '../lib/components/Hero.svelte';
</script>

<div>
	<Hero />
	<CustomerLogos />
	<Services />
	<CTA />
	<CastStudies />
	<WorkingProcess />
	<TheTeam />
	<ContactUs />
</div>

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
