<script>
    import screen from '$lib/assets/images/sleepyheadappphone.png';
    import moon from '$lib/assets/images/moon-background.png';
</script>

<div class="container h-full mx-auto flex justify-center items-center px-4 sm:px-6 md:px-8">
    <div class="space-y-5 text-center w-full max-w-md sm:max-w-lg">
        <div
            id="moondiv"
            class="flex justify-center items-center"
            style="background-image: url({moon});"
        >
            <img
                alt="screenshot of app on android phone"
                src={screen}
                class="w-full sm:w-3/4 lg:w-1/2"
            />
        </div>

        <h1 class="text-lg sm:text-xl lg:text-2xl font-bold">
            Use white noise to help you sleep
        </h1>
        <p class="text-sm sm:text-base leading-relaxed">
            White noise is a type of sound that contains a blend of frequencies that span the audible range. It is commonly used to help people fall asleep and stay asleep. Here are some benefits:
        </p>

        <!-- Bullet Points Section -->
        <ul class="text-left sm:text-center list-disc list-inside space-y-2 text-sm sm:text-base">
            <li>Blocks out distracting noises: Helps block out traffic, noisy neighbors, etc.</li>
            <li>Promotes relaxation: The consistent and soothing sound reduces stress and anxiety.</li>
            <li>Creates a familiar environment: Mimics comforting sounds like those in the womb.</li>
            <li>Reduces sensitivity to other sounds: Masks sudden noises like barking dogs or slamming doors.</li>
            <li>Improves sleep quality: Reduces awakenings and increases deep sleep time.</li>
        </ul>

        <div class="space-y-3 pb-10">
            <div class="flex flex-col sm:flex-row sm:justify-center sm:space-x-4 space-y-2 sm:space-y-0">
                <a
                    href="https://play.google.com/store/apps/details?id=edu.curtin.sleepyhead"
                    type="button"
                    class="btn variant-filled-primary text-sm sm:text-base px-4 py-2"
                >
                    App on Google Play
                </a>
                <a
                    href="https://www.instagram.com/dwellerdoesart"
                    type="button"
                    class="btn variant-filled-primary text-sm sm:text-base px-4 py-2"
                >
                    UI icons by @dwellerdoesart
                </a>
                <a
                    href="https://github.com/shades87/Sleepyhead"
                    type="button"
                    class="btn variant-filled-primary text-sm sm:text-base px-4 py-2"
                >
                    Github
                </a>
                <a
                    href="/sleepyhead-privacy-policy.html"
                    type="button"
                    class="btn variant-filled-primary text-sm sm:text-base px-4 py-2"
                >
                    Privacy Policy
                </a>
            </div>
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

    #moondiv {
        background-size: 5%;
        animation: pan 180s linear infinite;
    }
</style>
