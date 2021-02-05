<template>
    <div class="flex flex-col h-screen w-full bg-secondary px-5">
        <p class="font-quicksand font-bold text-white text-xl mt-4 mb-6">
            Quick Links
        </p>
        <section
            class="ref-links grid grid-cols-2 gap-4 w-10/12 md:w-2/5 text-center text-white font-quicksand font-semibold mb-8"
        >
            <a
                @click="scroll"
                class="bg-primary px-4 py-2 rounded-md rounded-tl-3xl rounded-br-3xl"
                >Biography</a
            >
            <a
                @click="scrollMeTo('project')"
                class="bg-primary px-4 py-2 rounded-md rounded-tl-3xl rounded-br-3xl"
                >Project</a
            >
            <a
                @click="scrollMeTo('art')"
                class="bg-primary px-4 py-2 rounded-md rounded-tl-3xl rounded-br-3xl"
                >Art Gallery</a
            >
        </section>
        <section
            class="ref-links grid grid-cols-2 gap-4 w-10/12 md:w-2/5 text-center text-white font-quicksand font-semibold"
        >
            <a
                href="#!"
                class="bg-none border-2 border-primary py-2 rounded-md rounded-tl-3xl rounded-br-3xl focus:bg-primary"
                >Discord Server</a
            >
            <a
                href="#!"
                class="bg-none border-2 border-primary px-4 py-2 rounded-md rounded-tl-3xl rounded-br-3xl focus:bg-primary"
                >osu!</a
            >
            <a
                href="#!"
                class="bg-none border-2 border-primary px-4 py-2 rounded-md rounded-tl-3xl rounded-br-3xl focus:bg-primary"
                >Steam</a
            >
        </section>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
.ref-links a:hover {
    @apply rounded-tl-md;
    @apply rounded-tr-3xl;
    @apply rounded-bl-3xl;
    @apply rounded-br-md;
    @apply duration-300;
}
</style>
