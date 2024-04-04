<!--//sleepyhead-app--> 

<script>
    import screen from '$lib/assets/images/sleepyheadappphone.png'
    import moon from '$lib/assets/images/moon-background.png'
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
		<div id="moondiv" class="container h-full mx-auto flex justify-center items-center" style="background-image: url({moon}); ">
		    <center><img alt="screenshot of app on android phone" src={screen} width="400"/></center>
        </div>
        <h1 class="h1 flex justify-center">Use white noise to help you sleep</h1>
		<p class="justify-center">White noise is a type of sound that contains a blend of frequencies that span the audible range. It is commonly used to help people fall asleep and stay asleep, and there are several benefits of using white noise for this purpose, including:</p>

        <p class="justify-center">Blocks out distracting noises: White noise can help block out distracting noises from the environment, such as traffic or noisy neighbors, which can make it easier for someone to fall asleep and stay asleep.</p>
            
        <p class="justify-center">Promotes relaxation: The consistent and soothing sound of white noise can promote relaxation, which can help reduce stress and anxiety and improve the quality of sleep.</p>
            
        <p class="justify-center">Creates a familiar environment: White noise can create a familiar environment, similar to the sound of being in the womb, which can be comforting and calming for some people.</p>
            
        <p class="justify-center"> Reduces sensitivity to other sounds: By masking other sounds, white noise can reduce sensitivity to other sounds that might otherwise wake someone up during the night, such as a dog barking or a door slamming.</p>
            
        <p class="justify-center">Improves sleep quality: Studies have shown that using white noise can improve the quality of sleep by reducing the number of times someone wakes up during the night and increasing the amount of time spent in deep sleep. </p>
        <center>
            <div class="btn-group variant-filled-primary">
                <a href="https://play.google.com/store/apps/details?id=edu.curtin.sleepyhead" type="button" class="btn variant-filled-primary">App on Google Play</a>
                <a href="https://www.instagram.com/dwellerdoesart" type="button" class="btn variant-filled-primary">UI icons by @dwellerdoesart</a>
                <a href="https://github.com/shades87/Sleepyhead" type="button" class="btn variant-filled-primary">Github</a>
                <a href="/sleepyhead-privacy-policy.html" type="button" class="btn variant-filled-primary">Privacy policy</a>
            </div>
        </center>
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

	#moondiv {
	background-size: 5%;
	animation: pan 180s linear infinite; 
  }
</style>