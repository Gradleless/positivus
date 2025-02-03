<script lang="ts">
	interface Service {
		title: string[];
		icon: string;
		image: string;
		link: string;
		variant: 'light' | 'green' | 'dark';
	}

	const services: Service[] = [
		{
			title: ['Search Engine', 'Optimization'],
			icon: '/Icon.png',
			image: '/tokyo-magnifier-web-search-with-elements 2.png',
			link: '#search-engine-optimization',
			variant: 'light'
		},
		{
			title: ['Pay-per-click', 'advertising'],
			icon: '/Icon.png',
			image: '/tokyo-selecting-a-value-in-the-browser-window 1.png',
			link: '#pay-per-click',
			variant: 'green'
		},
		{
			title: ['Social Media', 'Marketing'],
			icon: '/Icon (2).png',
			image: '/tokyo-browser-window-with-emoticon-likes-and-stars-around 2.png',
			link: '#social-media',
			variant: 'dark'
		},
		{
			title: ['Email', 'Marketing'],
			icon: '/Icon.png',
			image: '/tokyo-sending-messages-from-one-place-to-another 1.png',
			link: '#email-marketing',
			variant: 'light'
		},
		{
			title: ['Content', 'Creation'],
			icon: '/Icon.png',
			image: '/tokyo-many-browser-windows-with-different-information 1.png',
			link: '#content-creation',
			variant: 'green'
		},
		{
			title: ['Analytics and', 'Tracking'],
			icon: '/Icon (2).png',
			image: '/tokyo-volumetric-analytics-of-different-types-in-web-browsers 2.png',
			link: '#analytics',
			variant: 'dark'
		}
	];

	const getVariantClasses = (variant: Service['variant']) => {
		switch (variant) {
			case 'light':
				return {
					container: 'bg-gray-100',
					title: 'bg-[#B9FF66]',
					text: 'text-black'
				};
			case 'green':
				return {
					container: 'bg-[#B9FF66]',
					title: 'bg-white',
					text: 'text-black'
				};
			case 'dark':
				return {
					container: 'bg-[#191A23]',
					title: 'bg-white',
					text: 'text-white'
				};
		}
	};
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-28">
	<!-- First Part: 1 row 2 cols -->
	<div class="just mb-12 flex flex-col items-center md:flex-row">
		<div class="flex w-fit flex-col md:flex-row items-center p-4 text-center md:w-auto">
			<h2 class="rounded-lg bg-[#B9FF66] p-1 text-3xl font-bold">Services</h2>
			<p class="mt-2 md:w-[600px]">
				At our digital marketing agency, we offer a range of services to help businesses grow and
				succeed online. These services include:
			</p>
		</div>
	</div>

	<!-- Second Part: Grid with 1 row 2 cols, 1 col if mobile -->
	<div class="grid grid-cols-1 gap-8 md:grid-cols-2">
		{#each services as service}
			<a
				href={service.link}
				class="flex items-center justify-between rounded-[32px] border border-b-8 border-black p-4 hover:border-b-[1px] hover:pb-[1.438rem] duration-200 {getVariantClasses(
					service.variant
				).container}"
			>
				<div>
					{#each service.title as line, i}
						<h3
							class="ml-4 {i === 0 ? 'mt-6' : 'mt-0'} w-fit rounded-lg {getVariantClasses(
								service.variant
							).title} p-2 text-4xl font-bold leading-[40px]"
						>
							{line}
						</h3>
					{/each}
					<div class="ml-4 mt-10 flex items-center">
						<img src={service.icon} alt="Icon" class="mr-2 h-8 w-8" />
						<p class="font-medium {getVariantClasses(service.variant).text}">Learn More</p>
					</div>
				</div>
				<div class="ml-0">
					<img src={service.image} alt="Description" class="h-60 w-60 object-scale-down" />
				</div>
			</a>
		{/each}
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
