<script>
    import profile from '$lib/assets/images/grad-pic-circle.png'
    import star from '$lib/assets/images/star.png'
</script>

<div class="container h-full mx-auto flex justify-center items-center center">
	<div class="space-y-5 justify-center items-center center">
		
		<div  id="stardiv"  style="background-image: url({star}); "><center><img alt="Daniel wearing graduation outfit" class="justify-center items-center center" src={profile} width="200"/></center></div>

		<p  class="space-y-5 justify-center items-center center">Meet Daniel! Daniel (BA, BEd, BComp) is a computer scientist with a passion for AI, mobile application development, and the theory behind computer science. With a keen eye for detail and a knack for problem-solving, Daniel is well-equipped to tackle complex coding challenges and bring innovative ideas to life.</p>


            <p>Throughout their university journey, Daniel has gained valuable experience in various programming languages and tools, including Go, Python, Java, Kotlin, and C. Additionally, they have expertise in front-end web development languages, frameworks and markup languages like Javascript, React, HTML and CSS.</p>
            
            
            <p>As a dedicated and collaborative team player, Daniel enjoys working with others to bring projects to fruition. Their strong communication skills and ability to think outside the box make them an asset to any project.</p>
        
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