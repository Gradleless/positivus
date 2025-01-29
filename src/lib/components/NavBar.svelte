<script>
	let menuOpen = false;

	function toggleMenu() {
		menuOpen = !menuOpen;
	}
</script>

<div
	class="h-17 space-grotesk-500 flex items-center justify-between bg-white px-4 py-4 shadow-md md:px-28"
>
	<div class="text-2xl font-bold">
		<img src="/Logo.png" alt="Logo" class="h-8 w-auto md:h-12" />
	</div>
	<div class="hidden items-center gap-4 md:flex md:gap-16">
		<a href="#about-us" class="text-gray-800">About Us</a>
		<a href="#services" class="text-gray-800">Services</a>
		<a href="#use-cases" class="text-gray-800">Use Cases</a>
		<a href="#pricing" class="text-gray-800">Pricing</a>
		<a href="#blog" class="text-gray-800">Blog</a>
		<button
			class="rounded-xl border border-black bg-white px-4 py-2 text-black transition ease-in-out hover:bg-[#B9FF66] md:px-[35px] md:py-[20px]"
		>
			Request a Quote
		</button>
	</div>
	<div class="md:hidden">
		<button id="menu-button" class="text-gray-800" on:click={toggleMenu}>
			<svg
				class="h-6 w-6"
				fill="none"
				stroke="currentColor"
				viewBox="0 0 24 24"
				xmlns="http://www.w3.org/2000/svg"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M4 6h16M4 12h16m-7 6h7"
				></path>
			</svg>
		</button>
	</div>
</div>

<!-- Mobile Menu -->
{#if menuOpen}
	<div
		id="mobile-menu"
		class="space-grotesk-500 flex flex-col items-start gap-4 bg-white p-4 shadow-md md:hidden"
	>
		<a href="#about-us" class="text-gray-800">About Us</a>
		<a href="#services" class="text-gray-800">Services</a>
		<a href="#use-cases" class="text-gray-800">Use Cases</a>
		<a href="#pricing" class="text-gray-800">Pricing</a>
		<a href="#blog" class="text-gray-800">Blog</a>
		<button
			class="rounded-xl border border-black bg-white px-4 py-2 text-black transition ease-in-out hover:bg-[#B9FF66]"
		>
			Request a Quote
		</button>
	</div>
{/if}

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
