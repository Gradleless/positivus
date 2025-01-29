<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div
	class="h-17 space-grotesk-500 flex items-center justify-between bg-white px-4 py-4 shadow-md md:px-64"
>
	<div class="text-2xl font-bold">
		<img src="/Logo.png" alt="Logo" />
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
		<button id="menu-button" class="text-gray-800">
			<i class="fas fa-bars"></i>
		</button>
	</div>
</div>

<!-- Mobile Menu -->
<div
	id="mobile-menu"
	class="flex hidden flex-col items-start gap-4 bg-white p-4 shadow-md md:hidden"
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
{@render children()}

<footer
	class="space-grotesk-500 mx-0 rounded-tl-3xl rounded-tr-3xl bg-[#191A23] py-8 text-xs text-white md:mx-32 md:text-base"
>
	<div class="container mx-auto">
		<!-- First Row -->
		<div class="mb-8 flex flex-col items-center justify-between md:flex-row">
			<div class="mb-4 text-2xl font-bold md:mb-0">
				<img src="/Logo(1).png" alt="Logo" />
			</div>
			<div class="flex flex-col items-center justify-center gap-5 md:flex-row">
				<a href="#about-us" class="text-gray-300">About Us</a>
				<a href="#services" class="text-gray-300">Services</a>
				<a href="#use-cases" class="text-gray-300">Use Cases</a>
				<a href="#pricing" class="text-gray-300">Pricing</a>
				<a href="#blog" class="text-gray-300">Blog</a>
			</div>
			<div class="mt-4 flex gap-4 md:mt-0">
				<div
					class="flex h-8 w-8 items-center justify-center rounded-full bg-white text-black hover:bg-gray-600"
				>
					<!-- svelte-ignore a11y_consider_explicit_label -->
					<a href="#linkedin">
						<i class="fab fa-linkedin-in"></i>
					</a>
				</div>
				<div
					class="flex h-8 w-8 items-center justify-center rounded-full bg-white text-black hover:bg-gray-600"
				>
					<!-- svelte-ignore a11y_consider_explicit_label -->
					<a href="#facebook">
						<i class="fab fa-facebook-f"></i>
					</a>
				</div>
				<div
					class="flex h-8 w-8 items-center justify-center rounded-full bg-white text-black hover:bg-gray-600"
				>
					<!-- svelte-ignore a11y_consider_explicit_label -->
					<a href="#twitter">
						<i class="fab fa-twitter"></i>
					</a>
				</div>
			</div>
		</div>
		<!-- Second Row -->
		<div class="mb-8 flex flex-col items-center justify-between md:flex-row">
			<div class="flex w-full flex-col items-center gap-4 md:items-start">
				<p class="w-fit rounded-lg bg-[#B9FF66] px-2 text-lg text-black">Contact Us:</p>
				<p>Email: info@positivus.com</p>
				<p>Phone: 555-567-8901</p>
				<p>Address: 1234 Main St Moonstone City, Stardust State 12345</p>
			</div>
			<div class="mt-4 flex h-40 w-full items-center rounded-xl bg-[#292A32] md:mt-0">
				<form
					class="flex w-full flex-col items-center gap-4 px-4 py-4 md:flex-row md:gap-x-4 md:px-32 md:py-10"
				>
					<input
						type="email"
						placeholder="Enter your email"
						class="flex-grow rounded-xl border border-gray-300 bg-[#292A32] px-4 py-2"
					/>
					<button type="submit" class="rounded-xl bg-[#B9FF66] px-9 py-5 text-lg text-black">
						Subscribe to News
					</button>
				</form>
			</div>
		</div>
		<!-- Third Row -->
		<div class="flex flex-col items-center gap-4 md:flex-row md:gap-x-4">
			<p class="text-center">© 2023 Positivus. All Rights Reserved.</p>
			<p class="text-center">Privacy Policy</p>
		</div>
	</div>
</footer>

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
