<section class="space-grotesk-400 px-6 py-12 md:px-40">
	<div class="mb-16 flex flex-col items-center justify-center gap-x-8 text-center md:flex-row">
		<h2 class="rounded-xl bg-[#B9FF66] p-1 text-4xl font-bold">Contact Us!</h2>
		<h3 class="font-base mt-2 text-base text-black">
			Connect with Us: Let's Discuss Your Digital Marketing Needs
		</h3>
	</div>

	<!-- Contact Us Section -->
	<div class="relative mx-6 space-y-8 rounded-[45px] bg-[#F3F3F3] p-6 md:p-10">
		<!-- Image Positioned Relatively to the Right -->
		
		<!-- First Row: Radio Buttons -->
		<div class="flex flex-col items-start justify-start gap-4 md:flex-row md:justify-start">
			<label class="flex items-center space-x-2">
				<input type="radio" name="contactReason" value="general" class="form-radio focus:ring-0 duration-200" />
				<span>Say Hi!</span>
			</label>
			<label class="flex items-center space-x-2">
				<input type="radio" name="contactReason" value="support" class="form-radio focus:ring-0 duration-200" />
				<span>Get a Quote</span>
			</label>
		</div>

		<!-- Second Row: Contact Form -->
		<form class="w-full space-y-4 xl:w-[50rem] relative z-10">
			<div class="flex flex-col">
				<label for="name" class="mb-2 font-medium">Name*</label>
				<input
					type="text"
					id="name"
					name="name"
					class="rounded-[14px] border border-black p-3 md:p-5 focus:ring-1 focus:ring-green-600 focus:border-green-600 duration-200"
					placeholder="Enter your name"
					required
				/>
			</div>
			<div class="flex flex-col">
				<label for="email" class="mb-2 font-medium">Email*</label>
				<input
					type="email"
					id="email"
					name="email"
					class="rounded-[14px] border border-black p-3 md:p-5 focus:ring-1 focus:ring-green-600 focus:border-green-600 duration-200"
					placeholder="Enter your email"
					required
				/>
			</div>
			<div class="flex flex-col">
				<label for="message" class="mb-2 font-medium">Message*</label>
				<textarea
					id="message"
					name="message"
					rows="4"
					class="rounded-[14px] border border-black p-3 md:p-5 focus:ring-1 focus:ring-green-600 focus:border-green-600 duration-200"
					placeholder="Enter your message"
					required
				></textarea>
			</div>
			<button type="submit" class="w-full rounded-[14px] bg-[#191A23] px-6 py-3 text-white hover:bg-[#191A23]/90 active:duration-0 active:bg-[#191A23]/80 duration-200">
				Send Message
			</button>
		</form>

		<img
		src="/Illustration (3).png"
		alt="Contact Us"
		class="absolute right-0 top-0 hidden h-auto w-[150px] z-0 md:block md:w-[300px]"
	/>
	</div>
</section>

<style>
	.form-radio:checked {
		background-color: #b9ff66;
		border-color: black;
	}

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
