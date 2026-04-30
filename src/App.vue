<script setup>
    import Hero from './components/Hero.vue';
    import Navbar from './components/Navbar.vue'
import SectionFirst from './components/SectionFirst.vue';
import SectionSecond from './components/SectionSecond.vue';
</script>

<template>

    <!-- Head -->
    <Navbar />
    <Hero />

    <!-- Sections -->
    <SectionFirst/>
    <SectionSecond/>

</template>