<script setup>

import {RouterLink} from "vue-router"
import {defineProps} from "vue"
const primary_color = "#9867FF";

defineProps({
    title: {
        type: String,
        default: "Unknown",
    },
    link: {
        type: String,
        default: "/",
    }
})
</script>

<template>
     <RouterLink :class="`text-white rounded-full px-2 py-2 flex items-center`" :to="link"
            :style="`background-color:${primary_color}`">
            <i :class="`p-3 text-gray-900 bg-white rounded-full pi pi-arrow-up-right me-2 `"
                :style="`color:${primary_color}`"></i>
            <span class="text-lg me-4"> {{ title }}</span>
        </RouterLink>
</template>