<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <!-- Top Bar -->
    <section class=" bg-purple-500 text-white font-light py-2">
        <div class="container flex justify-between  mx-auto">
            <div>
                <p><i class="pi pi-map-marker"></i> 6391 Elgin St. Celina, Delaware 10299, USA</p>
            </div>
            <div class="flex">
                <div class="me-2">
                    <p><i class="pi pi-envelope"></i> recrutie.infor@example.com</p>
                </div>
                <div class="me-2">
                    <p><i class="pi pi-phone"></i> (+12) 3456 7890</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Navbar -->
    <section class="container mx-auto py-6 ">
        <div class="flex justify-between">
            <RouterLink>
                <img src="@/assets/img/logo.png" alt="">
            </RouterLink>

            <ul class="flex justify-around">
                <li class="py-2 px-4">
                    <RouterLink to="/">
                        Home
                    </RouterLink>
                </li>
                <li class="py-2 px-4">
                    <RouterLink to="/about-us">
                        About Us
                    </RouterLink>
                </li>
                <li class="py-2 px-4">
                    <RouterLink to="/services">
                        Services
                    </RouterLink>
                </li>
                <li class="py-2 px-4">
                    <RouterLink to="/case-studies">
                        Case Studies
                    </RouterLink>
                </li>
                <li class="py-2 px-4">
                    <RouterLink to="/case-studies">
                        Blog
                    </RouterLink>
                </li>
                <li class="py-2 px-4">
                    <RouterLink to="/case-studies">
                        Contact Us
                    </RouterLink>
                </li>
            </ul>
        </div>
    </section>
</template>