<script setup lang="ts">
import HeroSection from './components/sections/HeroSection.vue';
import AboutSection from './components/sections/AboutSection.vue';
import SolutionsSection from './components/sections/SolutionsSection.vue';
import FeaturesSection from './components/sections/FeaturesSection.vue';
import CasesSection from './components/sections/CasesSection.vue';
import CtaSection from './components/sections/CtaSection.vue';
import TheFooter from './components/TheFooter.vue';

useHead({
  htmlAttrs: {
    class: 'scroll-smooth'
  }
})
</script>

<template>
  <NuxtLayout>
    <div class="flex flex-col min-h-screen">
      <HeroSection />
      <AboutSection />
      <SolutionsSection />
      <FeaturesSection />
      <CasesSection />
      <CtaSection />
      <TheFooter />
    </div>
  </NuxtLayout>
</template>