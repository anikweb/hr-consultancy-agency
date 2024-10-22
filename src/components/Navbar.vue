<script setup>
import { RouterLink } from 'vue-router'
const primary_color = "#9867FF";
</script>

<template>
    <!-- Top Bar -->
    <section class="py-3 text-white font-extralight" :style="`background-color:${primary_color}`">
        <div class="container flex items-center justify-between mx-auto text-sm poppins-thin">
            <div>
                <p><i class="pi pi-map-marker"></i> 6391 Elgin St. Celina, Delaware 10299, USA</p>
            </div>

            <div class="flex items-center after:pi-address-book">
                <div class="pe-4 border-right-white">
                    <p class="flex items-center"><i class="pi pi-envelope me-2"></i><span>
                            recrutie.infor@example.com</span></p>
                </div>
                <div class="ms-4">
                    <p class="flex items-center"><i class="pi pi-phone me-2"></i>
                        <a href="tel:+1234567890">(+12) 3456 7890</a>
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Navbar -->
    <section class="container py-6 mx-auto ">
        <div class="flex items-center justify-between">
            <RouterLink to="/">
                <img src="@/assets/img/logo.png" alt="">
            </RouterLink>

            <ul class="flex justify-around font-sans text-xl font-medium poppins-medium ">
                <li class="px-4 py-2">
                    <RouterLink to="/">
                        Home
                    </RouterLink>
                </li>
                <li class="px-4 py-2">
                    <RouterLink to="/about-us">
                        About Us
                    </RouterLink>
                </li>
                <li class="px-4 py-2">
                    <RouterLink to="/services">
                        Services
                    </RouterLink>
                </li>
                <li class="px-4 py-2">
                    <RouterLink to="/case-studies">
                        Case Studies
                    </RouterLink>
                </li>
                <li class="px-4 py-2">
                    <RouterLink to="/case-studies">
                        Blog
                    </RouterLink>
                </li>
                <li class="px-4 py-2">
                    <RouterLink to="/case-studies">
                        Contact Us
                    </RouterLink>
                </li>
            </ul>

            <RouterLink :class="`text-white rounded-full px-2 py-2 flex items-center`"
                :style="`background-color:${primary_color}`">
                <i :class="`p-3 text-gray-900 bg-white rounded-full pi pi-arrow-up-right me-2 `"
                    :style="`color:${primary_color}`"></i>
                <span class="text-lg me-4"> Get A Quote</span>
            </RouterLink>
        </div>
    </section>
</template>

<style scoped>
.border-right-white {
    border-right: 2px solid rgba(255, 255, 255, 0.315);
    ;
}
</style>