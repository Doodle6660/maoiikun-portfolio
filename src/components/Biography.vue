<template>
    <div
        class="flex flex-col h-screen w-full bg-secondary px-5 justify-center text-white font-quicksand"
    >
        <p class="font-bold text-2xl">Biography</p>
        <div class="flex flex-row w-full mt-6">
            <div class="flex flex-col w-1/2 text-xs gap-y-3">
                <p class="font-primary font-semibold text-xl">
                    Personal <span class="text-primary">Info</span>
                </p>
                <div class="flex flex-row space-x-1">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="w-4 h-4 stroke-2 stroke-current text-white"
                    >
                        <path
                            d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"
                        ></path>
                        <circle cx="12" cy="7" r="4"></circle>
                    </svg>
                    <p>Ziyad F. Zidane</p>
                </div>
                <div class="flex flex-row space-x-1">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="w-4 h-4 stroke-2 stroke-current text-white"
                    >
                        <path
                            d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
                        ></path>
                        <polyline points="22,6 12,13 2,6"></polyline>
                    </svg>
                    <p class="truncate">ziyadzidane69@gmail.com</p>
                </div>
                <div class="flex flex-row space-x-1">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="w-4 h-4 stroke-2 stroke-current text-white"
                    >
                        <path
                            d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"
                        ></path>
                    </svg>
                    <p>(+62) 821-1785-5840</p>
                </div>
                <div class="flex flex-row space-x-1">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="w-4 h-4 stroke-2 stroke-current text-white"
                    >
                        <path
                            d="M12 22s-8-4.5-8-11.8A8 8 0 0 1 12 2a8 8 0 0 1 8 8.2c0 7.3-8 11.8-8 11.8z"
                        />
                        <circle cx="12" cy="10" r="3" />
                    </svg>
                    <p>Bojongsoang, Bandung</p>
                </div>
            </div>
            <div class="w-1/2 font-bold text-right">
                <p>
                    Hi! I'm an 18-year-old maker who enjoys creating fun stuff.
                    :D
                </p>
            </div>
        </div>
        <div class="w-full space-y-3 mt-8 text-sm font-primary">
            <p>
                I am a Web and User Interface Designer based in
                <span class="font-semibold">Bandung, Indonesia,</span> I love
                building simple & clean websites that are easy to use and
                beautiful to look at
            </p>
            <p>
                I’ve been a big fan of
                <span class="font-semibold">programming</span> computers ever
                since I was a lil' booger. The process of creating something out
                of nothing has always been what I
                <span class="font-semibold">loved</span> most about it.
            </p>
            <p>
                I love to <span class="font-semibold">draw !</span>. I don’t
                really drawing about anything in particular, just whatever’s
                bouncing around in my head or from anime which I just watched.
                You can check out mah
                <span class="font-semibold text-primary border-b border-primary"
                    ><a @click="scrollMeTo('art')">art work</a></span
                >
                if you're interested, and I'd love it if you did !.
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Biography",
    data() {
        return {
            name: "Biography",
        }
    },
}
</script>

<style scoped></style>
