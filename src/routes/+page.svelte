<script>
	import shades from '$lib/assets/images/shades.png'
	import star from '$lib/assets/images/star.png'
</script>

<div id="stardiv" style="background-image: url({star}); ">
<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5 justify-center items-center" >
		<h1 class="h1 justify-center items-center">Daniel McFadyen</h1>
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

	#stardiv {
	margin-top: 30%;
  background-size: 20%; /* bigger on mobile */
  animation: pan 15s linear infinite;
}

/* For desktop (md = min-width: 768px) */
@media (min-width: 768px) {
  #stardiv {
	margin-top: 0%;
    background-size: 5%; /* smaller on desktop */
	animation: pan 180s
  }
}

  
  
	div{
	display: flex;
    flex-direction: column;
    align-items: center;
	}

 

</style>