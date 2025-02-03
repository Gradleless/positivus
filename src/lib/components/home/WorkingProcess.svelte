<script>
	import { slide } from 'svelte/transition';

	let steps = [
		'Consultation',
		'Research and Strategy Development',
		'Implementation',
		'Monitoring and Optimization',
		'Reporting and Communication',
		'Continual Improvement'
	];
	let accordions = Array(steps.length).fill(false);

	// @ts-ignore
	function toggleAccordion(index) {
		accordions = accordions.map((isOpen, i) => (i === index ? !isOpen : isOpen));
	}
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-40">
	<div class="mb-16 flex flex-col items-center gap-x-8 md:flex-row text-center">
		<h2 class="rounded-xl bg-[#B9FF66] p-1 text-4xl font-bold">Our Working Process</h2>
		<h3 class="font-base text-base text-black mt-2">
			Step-by-Step Guide to Achieving Your Business Goals
		</h3>
	</div>

	<!-- Accordion Cards -->
	{#each steps as step, index}
		<div
			class="my-5 w-full rounded-2xl p-5 transition-colors duration-300 lg:p-10"
			style="background-color: {accordions[index] ? '#B9FF66' : '#F3F3F3'}"
		>
			<div class="overflow-hidden rounded-lg transition-all duration-300">
				<button
					class="flex cursor-pointer items-center justify-between p-4 w-full"
					onclick={() => toggleAccordion(index)}
				>
					<div class="flex flex-row items-center">
						<span class="mr-4 text-3xl font-bold lg:text-6xl"
							>{String(index + 1).padStart(2, '0')}</span
						>
						<span class="font-xl text-base lg:text-2xl text-left">{step}</span>
					</div>
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-12 min-h-12 min-w-12 w-12 rounded-full border-2 border-black p-2.5 transition-all duration-200 {accordions[index] ? 'rotate-90' : ''}"
						viewBox="0 0 160 160"
					>
						<rect class="" x="60" width="40" height="160" />
						<rect
							class="{accordions[index] ? 'rotate-90' : ''}"
							y="60"
							width="160"
							height="40"
						/>
					</svg>
				</button>
				{#if accordions[index]}
					<div class="border-t border-black p-4 transition-all duration-300" transition:slide>
						<p>
							Details of {step} go here. This is the content that will be shown or hidden when the accordion
							is toggled.
						</p>
					</div>
				{/if}
			</div>
		</div>
	{/each}
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
