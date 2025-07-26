<!--//sleepyhead-app--> 

<script>
    import screen from '$lib/assets/images/sleepyheadappphone.png'
    import moon from '$lib/assets/images/moon-background.png'
</script>

<div class="hidden md:block container h-full w-full mx-auto flex justify-center items-center">
	<div class="space-y-5 w-full justify-center items-center">
		<div id="moondiv" class="flex justify-center items-center h-full w-full" style="background-image: url({moon}); ">
		    <img alt="screenshot of app on android phone" src={screen} width="600"/>
            <div>
                <h1 class="h1 flex justify-center mb-2">Use white noise to help you sleep</h1>
                <p>A free app designed to help you falls asleep by blocking out distracting noises</p>
                <p>Promotes relaxation</p>
                <p>Creates a familiar environment</p>
                <p>Reduces sensitivity to other sounds</p>
                <p>Improves sleep quality</p>
            </div>
            
        </div>

    
        <center>
            <div class="space-y-5 pb-20">
                <div class="btn-group variant-filled-primary">
                    <a href="https://play.google.com/store/apps/details?id=edu.curtin.sleepyhead" type="button" class="btn variant-filled-primary">App on Google Play</a>
                    <a href="https://www.instagram.com/dwellerdoesart" type="button" class="btn variant-filled-primary">UI icons by @dwellerdoesart</a>
                    <a href="https://github.com/shades87/Sleepyhead" type="button" class="btn variant-filled-primary">Github</a>
                    <a href="/sleepyhead-privacy-policy.html" type="button" class="btn variant-filled-primary">Privacy policy</a>
                </div>
            </div>
        </center>
	</div>
</div>
<div   class="block md:hidden">
    <img alt="Sleepyhead app displayed on phone" src={screen}/>
    <div class="text-center">
        <h1 class="h1 flex justify-center mb-2">Use white noise to help you sleep</h1>
        <p>A free app designed to help you falls asleep by blocking out distracting noises</p>
        <p>Promotes relaxation</p>
        <p>Creates a familiar environment</p>
        <p>Reduces sensitivity to other sounds</p>
        <p>Improves sleep quality</p>
    </div>

   <div class="w-full flex justify-center mt-4">
  <button class="btn variant-filled-primary">
    App on Google Play
  </button>
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
	background-size: 30%;
	animation: pan 15s linear infinite; 
  }

  @media (min-width: 768px) {
    #moondiv {
	background-size: 5%;
	animation: pan 180s linear infinite; 
  }
  }

</style>

