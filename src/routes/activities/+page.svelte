<script lang="ts">
	import video1 from '$lib/assets/gallery/video1.mp4';
	import image2 from '$lib/assets/gallery/image2.jpeg';
	import image3 from '$lib/assets/gallery/image3.jpeg';
	import image4 from '$lib/assets/gallery/image4.jpeg';
	import image5 from '$lib/assets/gallery/image5.jpeg';
	import image6 from '$lib/assets/gallery/image6.jpeg';
	import image7 from '$lib/assets/gallery/image7.jpeg';
	import image8 from '$lib/assets/gallery/image8.jpeg';
	import image9 from '$lib/assets/gallery/image9.jpeg';
	import image10 from '$lib/assets/gallery/image10.jpeg';

	let images_list = [image2, image3, image4, image5, image6, image7, image8, image9, image10];
</script>

<section class="overflow-hidden text-neutral-700 mt-6">
	<h2 class="mt-4 mb-4 text-3xl font-bold leading-tight align-middle text-center">Activities</h2>
	<div class="container mx-auto px-5 py-2 lg:px-32 lg:pt-12">
		<div class="-m-1 flex flex-wrap md:-m-2">
			<div class="flex w-full flex-wrap">
				<video class="w-full h-auto max-w-full p-1 md:p-2 rounded-lg" controls>
					<source class="rounded-lg" src={video1} type="video/mp4" />
				</video>
			</div>
			{#each images_list as image}
				<div class="flex w-1/2 flex-wrap">
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
