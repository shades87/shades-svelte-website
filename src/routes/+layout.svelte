<script lang="ts">
	import '../app.postcss';
	import { AppBar } from '@skeletonlabs/skeleton'
</script>

<AppBar>
	<div class="btn-group-horizonta variant-filled">
		<a href="/" type="button" class="btn variant-filled">home</a>
		<a href="/sleepyhead-app" type="button" class="btn variant-filled">sleepyhead app</a>
		<a href="/about" type="button" class="btn variant-filled">about</a>
	</div>
</AppBar>

<slot />
