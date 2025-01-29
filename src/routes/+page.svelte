<script>
	import CustomerLogos from '../lib/components/CustomerLogos.svelte';

	import Hero from '../lib/components/Hero.svelte';
</script>

<Hero />
<CustomerLogos />

<section class="space-grotesk-400 px-6 py-12 md:px-28">
	<!-- First Part: 1 row 2 cols -->
	<div class="just mb-12 flex flex-col items-center md:flex-row">
		<div class="w-fit items-center p-4 md:w-auto">
			<h2 class="rounded-lg bg-[#B9FF66] p-1 text-3xl font-bold">Services</h2>
		</div>
		<div class="w-[600px] items-center p-4">
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
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 text-4xl font-bold">Grid Column 1</h3>
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 text-4xl font-bold">Grid Column 1</h3>
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 text-4xl font-bold">Grid Column 1</h3>
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 text-4xl font-bold">Grid Column 1</h3>
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
					alt="Description"
					class="h-60 w-60 object-scale-down"
				/>
			</div>
		</div>
		<div
			class="flex items-center justify-between rounded-[32px] border border-b-8 border-black bg-gray-100 p-4"
		>
			<div>
				<h3 class=" ml-4 mt-6 text-4xl font-bold">Grid Column 1</h3>
				<p class="ml-4 mt-28">Content for the first grid column goes here.</p>
			</div>
			<div class="ml-4">
				<img
					src="/tokyo-magnifier-web-search-with-elements 2.png"
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
