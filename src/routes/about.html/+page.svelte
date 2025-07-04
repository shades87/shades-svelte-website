<script>
    import profile from '$lib/assets/images/grad.jpg'
    import star from '$lib/assets/images/star.png'

</script>

<div class="container h-full mx-auto flex justify-center items-center center">
	<div class="space-y-5 justify-center items-center">
		
		<div class="justify-items-center" id="stardiv"  style="background-image: url({star}); ">
			<div class="mt-5 justify-center card preset-filled-surface-100-900 border-[1px] border-primary-500 divide-primary-500 block max-w-md divide-y overflow-hidden">
			
			<header>
				<img src={profile} class="aspect-[21/9] w-full" alt="banner" />
			</header>

			<article class="space-y-4 p-4">
				<div>
				<h2 class="h6">Meet Daniel!</h2>
				<h3 class="h3">BA, BEd, BComp (Honours)</h3>
				</div>
				<p class="opacity-100">
				G'day! I'm a computer scientist with a passion for AI, mobile application development, and the theory behind computer science. With a keen eye for detail and a knack for problem-solving, I feel I am well-equipped to tackle complex coding challenges and bring innovative ideas to life.
				</p>
			</article>

			<footer class="flex items-center justify-between gap-4 p-4">
				<small class="opacity-60">Go, Python, Java, Kotlin, and C</small>
				<small class="opacity-60">Dedicated team player and strong communication skills</small>
			</footer>
		</div>
		</div>
		
		

		<p  class="space-y-5 justify-center items-center center"></p>

            <center><div class="btn-group variant-filled-primary">
                <a href="https://www.linkedin.com/in/daniel-mcfadyen-curtin/" type="button" class="btn variant-filled-primary">linkedin</a>
                <a href="https://www.instagram.com/lazyjazzfox/" type="button" class="btn variant-filled-primary">instagram</a>
                <a href="https://github.com/shades87" type="button" class="btn variant-filled-primary">github</a>
            </div></center>
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
	background-size: 5%;
	animation: pan 180s linear infinite; 
  }
  
</style>