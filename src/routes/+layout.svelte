<script lang="ts">
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton'
</script>

<AppBar background="bg-primary-500">
	<div class="btn-group-horizonta variant-filled-primary">
		<a href="/" type="button" class="btn variant-ringed">home</a>
		<a href="/sleepyhead-app.html" type="button" class="btn variant-ringed">sleepyhead app</a>
		<a href="/about.html" type="button" class="btn variant-ringed">about</a>
	</div>
</AppBar>

<slot />
