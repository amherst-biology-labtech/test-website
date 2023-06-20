<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container mx-auto flex justify-center mt-10">
	<div class="text-center flex flex-col items-center">
		<h2 class="h2">X lab @ Amherst College</h2>
	</div>
</div>
<div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
	<div class="md:flex">
		<div class="md:shrink-0">
		<img class="h-48 w-full object-cover md:h-full md:w-48" src="\lib\assets\national-cancer-institute-L7en7Lb-Ovc-unsplash.png" alt="Modern building architecture">
		</div>
		<div class="p-8">
		<div class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">Company retreats</div>
		<div class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Incredible accommodation for your team</div>
		<p class="mt-2 text-slate-500">Looking to take your team away on a retreat to enjoy awesome food and take in some sunshine? We have a list of places to do just that.</p>
		</div>
	</div>
</div>


<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style>
