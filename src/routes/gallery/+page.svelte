<script lang="ts">
	import image1 from '$lib/assets/gallery/image1.jpeg';

	let images_list = [image1];
</script>

<section class="overflow-hidden text-neutral-700 mt-6">
	<h2 class="mt-4 mb-4 text-3xl font-bold leading-tight align-middle text-center">Gallery</h2>
	<div class="container mx-auto px-5 py-2 lg:px-32 lg:pt-12">
		<div class="-m-1 flex flex-wrap md:-m-2 items-center justify-center align-middle mb-10">
			{#each images_list as image}
				<div class="flex w-[75%] flex-wrap items-center justify-center align-middle">
					<div class="w-full p-1 md:p-2">
						<img
							alt="gallery"
							class="block h-full w-full rounded-lg object-cover object-center"
							src={image}
						/>
					</div>
				</div>
			{/each}
		</div>

		<blockquote
			class="relative text-xl italic font-semibold text-gray-900 text-center justify-center align-middle px-[18rem]"
		>
			<svg
				aria-hidden="true"
				class="w-10 h-10 text-gray-400 dark:text-gray-600"
				viewBox="0 0 24 27"
				fill="none"
				xmlns="http://www.w3.org/2000/svg"
				><path
					d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z"
					fill="currentColor"
				/></svg
			>
			<p class="relative text-2xl text-center justify-center align-middle text-gray-900">
				"From Hope to Belief"
			</p>
		</blockquote>
	</div>
</section>
