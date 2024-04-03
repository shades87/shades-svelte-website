<script>
	import shades from '$lib/assets/images/shades.png'
	import star from '$lib/assets/images/star.png'
</script>

<div id="maindiv"  style="background-image: url({star}); ">
<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5 justify-center items-center" >
		<h1 class="h1 justify-center items-center">shadyshadyshades</h1>
		<img class="justify-center items-center" alt="Sunglasses logo" src={shades}/>
		<p class="justify-center items-center">app development!</p>
		<p><code class="code justify-center items-center">shadyshadyshades@hotmail.com</code></p>
	</div>
</div>
</div>

<style>

	@keyframes pan {
		0% {
			background-position: 0% 0%;
		}

		100% {
			background-position: 100% 0%;
		}
	}

	#maindiv {

	background-size: 5%;
	animation: pan 180s linear infinite;
    
  }
	div{
		display: flex;
    flex-direction: column;
    align-items: center;
	}

 

</style>