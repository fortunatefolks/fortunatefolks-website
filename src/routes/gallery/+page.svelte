<script lang="ts">
	import image1 from '$lib/assets/gallery/image1.jpeg';
	import image2 from '$lib/assets/gallery/image2.jpeg';
	import image3 from '$lib/assets/gallery/image3.jpeg';
	import image4 from '$lib/assets/gallery/image4.jpeg';
	import image5 from '$lib/assets/gallery/image5.jpeg';

	let images_list = [image1, image2, image3, image4, image5];
</script>

<section class="overflow-hidden text-neutral-700 mt-6">
	<h2 class="mt-4 mb-4 text-3xl font-bold leading-tight align-middle text-center">Gallery</h2>
	<div class="container mx-auto px-5 py-2 lg:px-32 lg:pt-12">
		<div class="-m-1 flex flex-wrap md:-m-2">
			{#each images_list as image}
				<div class="flex w-1/4 flex-wrap">
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
	</div>
</section>
