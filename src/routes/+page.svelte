<script lang="ts">
	import clapImage from '$lib/assets/images/clap.png';
</script>

<div
	class="bg-[url('$lib/assets/images/banner.jpg')] bg-no-repeat bg-center bg-cover py-56 bg-opacity-1 h-[530px]"
>
	<div class="max-w-2xl mx-auto px-2 flex flex-wrap align-middle">
		<div class="max-w-md mx-auto">
			<h2 class="text-center font-bold text-3xl align-middle text-gray-900">
				We are a non-profit organization to provide entrepreneurship services for economic
				development in lagged areas
			</h2>
		</div>
	</div>
</div>
<div>
	<div class="flex">
		<a
			class="flex-1 py-8 bg-[#F8C919] text-yellow-darker no-underline hover--bg-yellow-darker hover--text-white"
			href="/"
		>
			<div class="flex justify-center">
				<div class="mx-auto flex items-center">
					<img src={clapImage} class="w-12 mr-2" alt="clap" />
					<div>
						<span class="uppercase text-sm font-bold">Join With Us</span>
						<span class="text-base sm--text-2xl block">Become a Vonluteer</span>
					</div>
				</div>
			</div>
		</a>
	</div>
</div>
