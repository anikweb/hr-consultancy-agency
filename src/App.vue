<script setup>
import { RouterView } from "vue-router"
import Navbar from '@/components/Navbar.vue'
import Breadcrumb from "@/components/Breadcrumb.vue";
</script>

<template>
    <Navbar />
    <Breadcrumb />
    <RouterView />
</template>