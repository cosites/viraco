<script>
    import "../app.css";
</script>

<main class="main relative flex-1 flex items-center justify-center">
    <div class="bg-black bg-opacity-60 p-14 rounded-lg backdrop-blur-sm">
        <slot></slot>
    </div>
</main>

<footer class="border-t border-neutral-800 bg-black bg-opacity-80 backdrop-blur-sm">
    <div class="text-sm text-neutral-400 my-3 mx-11 sm:mx-24 md:mx-48
                lg:mx-64 xl:mx-96 2xl:mx-[35rem]">
        <p>
            &copy 2023 Viraco, All Rights Reserved
        </p>
    </div>
</footer>

<style lang="postcss">
    :global(body) {
        @apply bg-black dark:text-white flex flex-col h-screen
        bg-no-repeat bg-cover;
        background-image: url('/background-image.jpg');
    }
    :global(h1) { @apply text-3xl my-3; }
    :global(h2) { @apply text-2xl my-2; }
    :global(h3) { @apply text-xl; }
    :global(section) { @apply mb-5; }
</style>