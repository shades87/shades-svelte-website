<script>
    import profile from '$lib/assets/images/grad-pic-circle.png';
    import star from '$lib/assets/images/star.png';
</script>

<div class="container mx-auto flex justify-center items-center h-full px-4 sm:px-6 md:px-8">
    <div class="space-y-5 flex flex-col justify-center items-center">
        <div
            id="stardiv"
            class="flex justify-center items-center"
            style="background-image: url({star});"
        >
            <img
                alt="Daniel wearing graduation outfit"
                class="rounded-full"
                src={profile}
                width="200"
                class="w-32 sm:w-40 md:w-48 lg:w-56"
            />
        </div>

        <p class="text-sm sm:text-base md:text-lg text-center">
            Meet Daniel! Daniel (BA, BEd, BComp) is a computer scientist with a passion for AI, mobile application development, and the theory behind computer science. With a keen eye for detail and a knack for problem-solving, Daniel is well-equipped to tackle complex coding challenges and bring innovative ideas to life.
        </p>

        <p class="text-sm sm:text-base md:text-lg text-center">
            Throughout their university journey, Daniel has gained valuable experience in various programming languages and tools, including Go, Python, Java, Kotlin, and C. Additionally, they have expertise in front-end web development languages, frameworks, and markup languages like Javascript, React, HTML, and CSS.
        </p>

        <p class="text-sm sm:text-base md:text-lg text-center">
            As a dedicated and collaborative team player, Daniel enjoys working with others to bring projects to fruition. Their strong communication skills and ability to think outside the box make them an asset to any project.
        </p>

        <div class="btn-group variant-filled-primary space-x-3 text-center">
            <a
                href="https://www.linkedin.com/in/daniel-mcfadyen-curtin/"
                type="button"
                class="btn variant-filled-primary"
            >
                LinkedIn
            </a>
            <a
                href="https://www.instagram.com/lazyjazzfox/"
                type="button"
                class="btn variant-filled-primary"
            >
                Instagram
            </a>
            <a
                href="https://github.com/shades87"
                type="button"
                class="btn variant-filled-primary"
            >
                GitHub
            </a>
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
        background-size: 5%;
        animation: pan 180s linear infinite;
    }
</style>
