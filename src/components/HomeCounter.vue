<script setup>

import {defineProps} from 'vue'

defineProps({
    title: {
        type: String
    },
    number: {
        type: String
    }
})

</script>
<template>
    <div>
        <h1 class="text-5xl font-bold">{{ number }}</h1>
        <h4 class="text-xl">{{ title }}</h4>
    </div>
</template>

<style scoped>
 h1{
    color:  #9867FF;
 }
</style>