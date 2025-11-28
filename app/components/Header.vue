<script setup lang="ts">
import NavSocialGroup from "./NavSocialGroup.vue";
</script>

<template>
  <header class="w-full max-w-7xl mx-auto flex items-center justify-between gap-4 px-4 sm:px-6 py-6 sm:py-8 bg-transparent text-slate-100">
    <h1 class="text-xl sm:text-2xl lg:text-3xl font-bold select-none font-orbitron whitespace-nowrap">
      Nova Forge
    </h1>
    <nav class="hidden lg:flex gap-4 xl:gap-8 items-center">
      <NuxtLink class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base" to="/">
        Smart Contracts
      </NuxtLink>
      <NuxtLink class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base" to="/projects">
        Services
      </NuxtLink>
      <NuxtLink class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base" to="/projects">
        Solutions
      </NuxtLink>
      <NuxtLink class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base" to="/projects">
        Roadmap
      </NuxtLink>
      <NuxtLink class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base">
        Contact Us
      </NuxtLink>
    </nav>

    <NavSocialGroup class="flex-shrink-0" />
  </header>
</template>