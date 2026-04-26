<script setup>
    import Hero from './components/Hero.vue';
    import Navbar from './components/Navbar.vue'
</script>

<template>

    <Navbar />
    <Hero />

    <section class="px-30 grid grid-cols-2 gap-12 mt-12">
        <div class="w-full h-100 bg-red-100"></div>
        <div class="w-full h-100">
            <h2 class="text-6xl font-bold mb-8">Technical Views</h2>
            <p class="text-xl">A research tool that combines automated<br/>algorithm with expert market analysis to<br/>help you create better trading plans.</p>
            <div class="flex mt-8">
                <a href="#" class="w-max block bg-blue-500 text-white py-3 px-12 rounded-full me-6">Learn More</a>
                <a href="#" class="w-max block outline-3 outline-blue-500 text-blue-500 py-3 px-12 rounded-full">Explore</a>
            </div>
        </div>
    </section>

</template>