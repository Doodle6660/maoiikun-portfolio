<template>
    <div class="home">
        <app-hello></app-hello>
        <app-link></app-link>
        <app-biography></app-biography>
    </div>
</template>

<script>
import Hello from "@/components/Hello.vue"
import QuickLinks from "@/components/QuickLinks.vue"
import Biography from "@/components/Biography.vue"

export default {
    data() {
        return {}
    },
    components: {
        "app-hello": Hello,
        "app-link": QuickLinks,
        "app-biography": Biography,
    },
}
</script>
