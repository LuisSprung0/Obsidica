<script>
    // Any component logic goes here
</script>
<svelte:head>
    <meta charset="UTF-8">
    <title>Obsidica</title>
    <meta name="description" content="Obsidica is a personal project im developing, not sure what I want with it yet!">
    <meta name="keywords" content="obsidica, portfolio, design, web, obsidian, UI">
    <meta name="author" content="Luis Sprung">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</svelte:head>

<div class="bg-neutral-900 h-screen w-screen relative">
    <div class="flex flex-col justify-center items-center h-full w-full text-center">
        <div id="logo" class="h-64 sm:h-96 md:h-128 mb-8">
            <img 
                src="/images/logo.svg" 
                alt="Obsidica logo" 
                class="w-full h-full duration-300 hover:scale-102 ease-out"
            />
        </div>

        <div id="name">
            <p class="font-[MontserratAlt1] font-extralight text-6xl text-neutral-300">OBSIDICA</p>
        </div>
    </div>

    <div class="absolute bottom-2 right-2 text-neutral-500">
        <p>
            <a 
                href="https://www.linkedin.com/in/luis-sprung-544480347/"
                class="underline underline-offset-3 hover:decoration-2 decoration-neutral-500 text-neutral-600"
                target="_blank"
            >
            Made By: Luis Sprung
            </a>
        </p>
    </div>
</div>