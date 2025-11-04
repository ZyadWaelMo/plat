<script setup lang="ts">
useSeoMeta({
    title: "plat - about",
    description: "Special recipes for you!",
    ogTitle: "plat - about",
    ogDescription: "Special recipes for you!",
    ogImage: "/nuxt-course-hero.png",
    ogUrl: `http://localhost:3000/about`,
    twitterTitle: "plat - about",
    twitterDescription: "Special recipes for you!",
    twitterImage: "/nuxt-course-hero.png",
    twitterCard: "summary",
});
</script>


<template>
    <main>
        <section class="container py-20">
            <h1 class="text-6xl font-bold mb-6 text-balance">About plat:</h1>
            <p class="text-xl font-medium mb-6 text-balance max-w-screen-lg">
                plat is a recipe application based on the dummyJSON API, created by <span class="font-extrabold">Zyad Wael</span> for my Nuxt practice projects.
            </p>
        </section>
    </main>
</template>