<script>
	import Services from './Services.svelte';

	import CustomerLogos from './CustomerLogos.svelte';

	import Hero from './Hero.svelte';
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-40">
	<div
		class="relative flex flex-col items-center justify-between rounded-[45px] bg-[#F3F3F3] px-4 py-5 md:flex-row md:px-20 md:py-10"
	>
		<div class="w-full p-4 md:w-1/2">
			<h1 class="text-4xl font-bold md:text-4xl">Let&apos;s make things happen</h1>
			<h3 class="mt-4 text-base md:text-base">
				Contact us today to learn more about how our digital marketing services can help your
				business grow and succeed online.
			</h3>
			<button class="mt-6 rounded-xl bg-[#191A23] px-6 py-3 text-white"
				>Get your free proposal</button
			>
		</div>
		<div class="relative w-full p-4 md:w-1/2">
			<!-- svelte-ignore a11y_img_redundant_alt -->
			<img
				src="/Illustration (2).png"
				alt="CTA Image"
				class="relative hidden h-auto w-full md:absolute md:right-[50px] md:top-[-130px] md:block md:h-[350px] md:w-auto"
			/>
		</div>
	</div>
</section>

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
