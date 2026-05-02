<script setup>
    import FooterComponent from './components/FooterComponent.vue';
    import Hero from './components/Hero.vue';
    import Navbar from './components/Navbar.vue'
    import SectionFifth from './components/SectionFifth.vue';
    import SectionFirst from './components/SectionFirst.vue';
    import SectionFourth from './components/SectionFourth.vue';
    import SectionSecond from './components/SectionSecond.vue';
    import SectionThird from './components/SectionThird.vue';
</script>

<template>

    <!-- Head -->
    <Navbar />
    <Hero />

    <!-- Sections -->
    <SectionFirst/>
    <SectionSecond/>
    <SectionThird/>
    <SectionFourth/>
    <SectionFifth/>

    <!-- Footer -->
    <FooterComponent/>

</template>