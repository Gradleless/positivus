<script>
	import CustomerLogos from './CustomerLogos.svelte';

	import Hero from './Hero.svelte';
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-28">
	<!-- First Part: 1 row 2 cols -->
	<div class="just mb-12 flex flex-col items-center md:flex-row">
		<div class="w-fit items-center p-4 md:w-auto">
			<h2 class="rounded-lg bg-[#B9FF66] p-1 text-3xl font-bold">Services</h2>
		</div>
		<div class="w-[400px] items-center p-4 md:w-[600px]">
			<p class="">
				At our digital marketing agency, we offer a range of services to help businesses grow and
				succeed online. These services include:
			</p>
		</div>
	</div>

	<!-- Second Part: Grid with 1 row 2 cols, 1 col if mobile -->
	<div class="grid grid-cols-1 gap-8 md:grid-cols-2">
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[40px]">
					Search Engine
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[30px]">
					Optimization
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon.png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-[#B9FF66] p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[40px]">
					Pay-per-click
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[30px]">
					advertising
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon.png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-selecting-a-value-in-the-browser-window 1.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-[#191A23] p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[40px]">
					Social Media
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[30px]">
					Marketing
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon (2).png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium text-white">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-browser-window-with-emoticon-likes-and-stars-around 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[40px]">
					Email
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[30px]">
					Marketing
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon.png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-sending-messages-from-one-place-to-another 1.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-[#B9FF66] p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[40px]">
					Content
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-white p-2 text-4xl font-bold leading-[30px]">
					Creation
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon.png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-many-browser-windows-with-different-information 1.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-[#191A23] p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[40px]">
					Analytics and
				</h3>
				<h3 class=" ml-4 mt-0 w-fit rounded-lg bg-[#B9FF66] p-2 text-4xl font-bold leading-[30px]">
					Tracking
				</h3>
				<div class="ml-4 mt-10 flex items-center">
					<img src="/Icon (2).png" alt="Icon" class="mr-2 h-8 w-8" />
					<p class="font-medium text-white">Learn More</p>
				</div>
			</div>
			<div class="ml-0">
				<img
					src="/tokyo-volumetric-analytics-of-different-types-in-web-browsers 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
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
