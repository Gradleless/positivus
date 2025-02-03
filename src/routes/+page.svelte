<script>
	import Hero from '$lib/components/home/Hero.svelte';
	import CastStudies from '$lib/components/home/CastStudies.svelte';
	import ContactUs from '$lib/components/home/ContactUs.svelte';
	import CustomerLogos from '$lib/components/home/CustomerLogos.svelte';
	import Services from '$lib/components/home/Services.svelte';

	import TheTeam from '$lib/components/home/TheTeam.svelte';
	import WorkingProcess from '$lib/components/home/WorkingProcess.svelte';
	import CTA from '$lib/components/home/CTA.svelte';

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
