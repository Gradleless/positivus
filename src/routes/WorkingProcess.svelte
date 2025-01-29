<script>
	let steps = [
		'Consultation',
		'Research and Strategy Development',
		'Implementation',
		'Monitoring and Optimization',
		'Reporting and Communication',
		'Continual Improvement'
	];
	let accordions = Array(steps.length).fill(false);

	function toggleAccordion(index) {
		accordions = accordions.map((isOpen, i) => (i === index ? !isOpen : isOpen));
	}
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-40">
	<div class="mb-16 flex flex-col items-center gap-x-8 md:flex-row">
		<h2 class="rounded-xl bg-[#B9FF66] p-1 text-4xl font-bold">Our Working Process</h2>
		<h3 class="font-base w-[400px] text-base text-black">
			Step-by-Step Guide to Achieving Your Business Goals
		</h3>
	</div>

	<!-- Accordion Cards -->
	{#each steps as step, index}
		<div
			class="my-5 w-full rounded-2xl p-10 transition-colors duration-300"
			style="background-color: {accordions[index] ? '#B9FF66' : '#F3F3F3'}"
		>
			<div class="overflow-hidden rounded-lg transition-all duration-300">
				<!-- svelte-ignore a11y_click_events_have_key_events -->
				<!-- svelte-ignore a11y_no_static_element_interactions -->
				<div
					class="flex cursor-pointer items-center justify-between p-4"
					on:click={() => toggleAccordion(index)}
				>
					<div class="flex flex-row items-center">
						<span class="mr-4 text-6xl font-bold">{String(index + 1).padStart(2, '0')}</span>
						<span class="font-xl text-2xl">{step}</span>
					</div>
					<button
						class="flex h-12 w-12 items-stretch justify-center rounded-full border border-black bg-gray-300 text-center text-5xl font-bold"
					>
						{accordions[index] ? '-' : '+'}
					</button>
				</div>
				{#if accordions[index]}
					<div class="border-t border-black p-4 transition-all duration-300">
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
