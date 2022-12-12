<script setup>
import IntroSectionVue from '../components/IntroSection.vue';
import Projects from '../components/Projects.vue'
import TechUsed from '../components/TechUsed.vue'
import FooterVue from '../components/Footer.vue';
</script>

<template>
  <main class="space-y-14 mb-10 container mx-auto min-h-screen pb-8 w-11/12 sm:pb-10 sm:w-9/12 md:w-7/12">
    <IntroSectionVue />
    <Projects />
    <TechUsed />
    
  </main>
  <FooterVue />
</template>