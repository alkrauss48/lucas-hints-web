<script>
	import logo from '$lib/images/lucas-hints.jpeg';
	import appStoreImg from '$lib/images/download-on-the-app-store.svg';
	import demoGif from '$lib/images/demo-lucas-hints.gif';

	const appStoreUrl = 'https://apps.apple.com/app/lucas-hints/id6596782787';
</script>

<svelte:head>
	<title>Lucas Hints</title>
	<meta
		name="description"
		content="Lucas Hints is an iOS app that helps you create fun, memorable stories with friends and family by kickstarting your creativity."
	/>
</svelte:head>

<section>
	<img class="logo mt-12" src={logo} alt="Lucas Hints logo" />

	<h1>
		Welcome to <span class="inline-block">Lucas Hints</span>
	</h1>

	<a href={appStoreUrl} target="_blank">
		<img src={appStoreImg} alt="Download Lucas Hints on the App Store" />
	</a>

	<p class="max-w-xl text-center">
		<strong>Lucas Hints</strong> is an iOS app that helps you create fun, memorable stories with friends
		and family by kickstarting your creativity.
	</p>

	<img class="mt-12" src={demoGif} alt="Download Lucas Hints on the App Store" />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
</style>
