<script>
	const teamMembers = [
		{
			name: 'John Smith',
			position: 'Marketing Expert',
			description:
				'John is a seasoned marketing expert with over 10 years of experience in digital marketing strategies and campaign management.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-1'
		},
		{
			name: 'Jane Doe',
			position: 'SEO Specialist',
			description:
				'Jane is an SEO specialist with a knack for improving search engine rankings and driving organic traffic.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-2'
		},
		{
			name: 'Alice Johnson',
			position: 'Content Strategist',
			description:
				'Alice is a content strategist who excels in creating compelling content that engages and converts.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-3'
		},
		{
			name: 'Bob Brown',
			position: 'PPC Manager',
			description:
				'Bob is a PPC manager with extensive experience in managing and optimizing pay-per-click campaigns.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-4'
		},
		{
			name: 'Charlie Davis',
			position: 'Social Media Manager',
			description:
				'Charlie is a social media manager who knows how to build and maintain a strong social media presence.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-5'
		},
		{
			name: 'Eve Wilson',
			position: 'Email Marketing Specialist',
			description:
				'Eve is an email marketing specialist with a talent for creating effective email campaigns that drive results.',
			image: '/Picture.png',
			linkedin: 'https://www.linkedin.com/in/team-member-6'
		}
	];
</script>

<section class="space-grotesk-400 px-6 py-12 md:px-40">
	<div class="mb-16 flex flex-col items-center gap-x-8 md:flex-row">
		<h2 class="rounded-xl bg-[#B9FF66] p-1 text-4xl font-bold">Team</h2>
		<h3 class="font-base text-base text-black mt-2">
			Meet the skilled and experienced team behind our successful digital marketing strategies
		</h3>
	</div>

	<!-- Team Cards Grid -->
	<div class="grid grid-cols-1 gap-8 xl:grid-cols-3">
		{#each teamMembers as member}
			<div class="relative rounded-[45px] border border-b-8 border-black p-12 duration-300 hover:border-b-[1px] hover:pb-[3.438rem]">
				<div class="mb-4 flex items-start justify-between">
					<div class="flex items-center">
						<img src={member.image} alt={member.name} class="mr-4 h-20 w-20" />
						<div>
							<h4 class="text-xl font-bold">{member.name}</h4>
							<p class="text-gray-600">{member.position}</p>
						</div>
					</div>
				</div>
				<a href={member.linkedin} target="_blank" class="shrink-0">
					<img src="/Social icon.png" alt="LinkedIn" class="h-8 w-8" />
				</a>
				<div class="mt-3 border-t border-black">
					<p class="mt-8 text-gray-600">{member.description}</p>
				</div>
			</div>
		{/each}
	</div>

	<!-- See All Team Button -->
	<div class="mt-8 flex justify-end">
		<button class="rounded-[14px] bg-[#191A23] px-20 py-5 text-white hover:bg-[#191A23]/90 active:duration-0 active:bg-[#191A23]/80 duration-200">See All Team</button>
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
