<script lang="ts">
	import '../styles/app_output.css';
	import headerLogo from '$lib/assets/images/ffwo-logo.png';
	import footerLogo from '$lib/assets/images/ffwo-logo-single.png';

	import Header from '$lib/components/Header/Header.svelte';
	import Footer from '$lib/components/Footer/Footer.svelte';
</script>

<svelte:head>
	<link
		href="https://fonts.googleapis.com/css?family=Lato:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i"
		rel="stylesheet"
	/>
	<link
		href="https://fonts.googleapis.com/css?family=Eczar:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i"
		rel="stylesheet"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/all.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/brands.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/duotone.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/fontawesome.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/light.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/regular.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/solid.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/codack04/github-cdn-service/font-awesome/6.1.0/css/thin.min.css"
	/>
</svelte:head>

<div class="w-full font-lato">
	<Header {headerLogo} />
	<slot />
	<Footer {footerLogo} />
</div>
