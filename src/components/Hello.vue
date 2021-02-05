<template>
    <div
        class="flex flex-col h-screen w-full bg-gradient-to-b from-primary to-secondary"
    >
        <header
            class="flex flex-row w-full h-16 justify-between items-center text-center text-white px-5"
        >
            <div class="w-1/5 flex justify-start">
                <logo-instagram></logo-instagram>
            </div>
            <div class="w-3/5 font-logo text-3xl">@maoiikun</div>
            <div class="w-1/5 flex justify-end">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="w-8 h-8 stroke-2 stroke-current text-white"
                >
                    <line x1="8" y1="6" x2="21" y2="6"></line>
                    <line x1="8" y1="12" x2="21" y2="12"></line>
                    <line x1="8" y1="18" x2="21" y2="18"></line>
                    <line x1="3" y1="6" x2="3.01" y2="6"></line>
                    <line x1="3" y1="12" x2="3.01" y2="12"></line>
                    <line x1="3" y1="18" x2="3.01" y2="18"></line>
                </svg>
            </div>
        </header>

        <section
            class="flex flex-col w-full h-full justify-center text-white px-6"
        >
            <div class="font-primary font-bold text-5xl mb-24">
                <p>Hello<span>.</span></p>
                <p>I am</p>
                <p>
                    maoiikun
                    <span class="text-xl font-light">aka.</span> Doodle,
                </p>
                <div class="text-2xl mt-8 font-medium font-quicksand">
                    <p>Front-End Developer &</p>
                    <p>UI/UX Designer</p>
                </div>
            </div>
            <p class="text-xl">
                Hi!
                <span class="font-semibold">I'm an 18-year-old maker</span> who
                enjoys building simple & clean websites that are easy to use and
                beautiful to look at.
            </p>
        </section>
    </div>
</template>

<script>
import Instagram from "@/assets/icon/Instagram.vue"

export default {
    components: {
        "logo-instagram": Instagram,
    },
}
</script>

<style scoped></style>
