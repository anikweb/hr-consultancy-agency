<script setup>
const primaryColor = "#9867FF";
</script>
<template>
    <section class="container mx-auto">
        <div>
            <h4 class="text-xl font-bold text-center" :style="`color:${primaryColor}`">/ who we are /</h4>
            <h1 class="mt-2 mb-16 text-5xl font-extrabold text-center">A Leading Global Provider <br> Of Recruitment
            </h1>

            <div class="grid grid-cols-1 gap-10 md:grid-cols-3">
                <div>
                    <img src="@/assets/img/home-about.jpg" alt="">
                </div>
                <div class="col-span-2 mx-8">
                    <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
                        doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore
                        veritatis et quasi architecto beatae.</p>


                    <div class="grid grid-cols-2 my-4 gap-7">
                        <div class="my-2">
                            <h2 class="text-2xl font-bold">Profile Highlighter</h2>
                            <p class="font-thin">Get highlighted by the company that you've been worked.
                            </p>
                        </div>
                        <div class="my-2">
                            <h2 class="text-2xl font-bold">Find Suitable Candidates</h2>
                            <p class="font-thin">Get highlighted by the company that
                                you’ve been worked.
                            </p>
                        </div>
                        <div class="my-2">
                            <h2 class="text-2xl font-bold">Leadership Training</h2>
                            <p class="font-thin">Get highlighted by the company that
                                you’ve been worked.
                            </p>
                        </div>
                        <div class="my-2">
                            <h2 class="text-2xl font-bold">Fast On Demand Service</h2>
                            <p class="font-thin">Get highlighted by the company that
                                you’ve been worked.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>