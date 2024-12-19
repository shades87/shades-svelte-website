<script>
    import shades from '$lib/assets/images/shades.png';
    import star from '$lib/assets/images/star.png';
</script>

<div
    id="stardiv"
    class="h-screen flex justify-center items-center"
    style="background-image: url({star});"
>
    <div class="container mx-auto flex flex-col justify-center items-center space-y-5 px-4 sm:px-6 md:px-8">
        <h1 class="text-2xl sm:text-3xl md:text-4xl font-bold text-center">
            shadyshadyshades
        </h1>
        <img
            alt="Sunglasses logo"
            src={shades}
            class="w-24 sm:w-36 md:w-48 lg:w-56"
        />
        <p class="text-sm sm:text-base md:text-lg text-center">
            App development!
        </p>
        <p>
            <code class="bg-gray-100 text-gray-800 px-2 py-1 rounded text-xs sm:text-sm md:text-base">
                shadyshadyshades@hotmail.com
            </code>
        </p>
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
