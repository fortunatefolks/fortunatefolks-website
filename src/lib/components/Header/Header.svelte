<script lang="ts">
	import mainLogo from '$lib/assets/images/ffwo-logo.png';

	import Nav from '$lib/components/Header/Nav/Nav.svelte';
</script>

<header class="bg-white shadow-md">
	<div class="container mx-auto px-2">
		<div class="flex justify-between items-center">
			<div class="flex flex-row">
				<img src={mainLogo} width="325px" alt="logo" />
			</div>

			<Nav />

			<div class="text-right">
				<button class="bg-[#F8C919] py-2 px-4 text-sm inline-block tracking-wide font-semibold"
					>Donate</button
				>
			</div>
		</div>
	</div>
</header>
