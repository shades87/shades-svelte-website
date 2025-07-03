<script lang="ts">
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton'
</script>

<svelte:head>
  <title>Computer Scientist - Daniel McFadyen</title>
</svelte:head>

<AppBar background="bg-primary-500">
	<div class="btn-group-horizontal variant-filled-primary">
		<a href="/" type="button" class="btn variant-ringed">home</a>
		<a href="/research" type="button" class="btn variant-ringed">research</a>
		<a href="/sleepyhead-app.html" type="button" class="btn variant-ringed">sleepyhead app</a>
		<a href="/about.html" type="button" class="btn variant-ringed">about</a>
	</div>
</AppBar>

<slot />
