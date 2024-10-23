<script setup>
import QuickLinkBtn from '@/components/QuickLinkBtn.vue'
import {defineProps} from "vue"
const primaryColor = '#9867FF'

defineProps({
    bgImage: {
        type: String,
        default: "/src/assets/img/services/service_back_1.png"
    },
    image: {
        type: String,
    },title: {
        type: String,
        default: "Recruitment Solution"
    },
    subtitle: {
        type: String,
        default: "Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium dolor…"
    },
    link: String
})
</script>

<template>
    <div class="px-8 py-4 rounded-lg shadow-xl" :style="`background-image:url('${bgImage}');background-repeat:no-repeat;background-position:bottom`">
        <h1 class="pt-4 text-2xl font-bold poppins-bold">{{ title }}</h1>
        <p class="mt-4 mb-6 font-thin text-gray-400">{{ subtitle }}</p>
            <QuickLinkBtn :link="link" title="Explore Now" :color="primaryColor"  />
            <img :src="image" alt="service" class="mt-24 mb-4">
    </div> 
</template>