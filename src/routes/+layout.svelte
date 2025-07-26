<script lang="ts">
	import { page } from '$app/stores'
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton'
	import { TabGroup, TabAnchor } from '@skeletonlabs/skeleton';
</script>

<svelte:head>
  <title>Computer Scientist - Daniel McFadyen</title>
</svelte:head>
<div class="hidden sm:block">
	<AppBar background="bg-primary-500">
	<div class="btn-group-horizontal variant-filled-primary">
		<a href="/" type="button" class="btn variant-ringed">home</a>
		<a href="/research.html" type="button" class="btn variant-ringed">research</a>
		<a href="/sleepyhead-app.html" type="button" class="btn variant-ringed">sleepyhead app</a>
		<a href="/about.html" type="button" class="btn variant-ringed">about</a>
		
	</div>
</AppBar>
</div>


<slot />

<div class="fixed bottom-0 left-0 w-full block sm:hidden mt-5">
	<TabGroup 
	justify="justify-center"
	active="variant-filled-primary"
	hover="hover:variant-soft-primary"
	flex="flex-1 lg:flex-none"
	rounded=""
	border=""
	class="bg-surface-100-800-token w-full"
>
	<TabAnchor href="/" selected={ $page.url.pathname === '/'}>
		<span>home</span>
	</TabAnchor>
	<TabAnchor href="/research.html" selected={ $page.url.pathname === '/research.html'}>

		<span>research</span>
	</TabAnchor>
	<TabAnchor href="/sleepyhead-app.html" selected={ $page.url.pathname === '/sleepyhead-app.html'}>

		<span>app</span>
	</TabAnchor>
	<TabAnchor href="/about.html" selected={ $page.url.pathname === '/about.html'}>

		<span>about</span>
	</TabAnchor>
	
</TabGroup>
</div>