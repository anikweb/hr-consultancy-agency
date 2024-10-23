<script setup>
import {RouterLink} from "vue-router"
import {defineProps} from 'vue'

defineProps({
    title: {
        type: String,
        default: "Unknown",
    },
    link: {
        type: String,
        default: "/"
    },
    color: {
        type: String,
        default: "text-gray-900"
    }
})


</script>
<template>
    <RouterLink :to="link" :class="`text-xl `"  :style="`color:${color}`">
        {{ title }}
        <i class="text-sm pi pi-arrow-up-right"></i>
    </RouterLink>
</template>