<script setup lang="ts">
import NavSocialGroup from "./NavSocialGroup.vue";
</script>

<template>
  <header class="w-full max-w-7xl mx-auto flex items-center justify-between gap-4 px-4 sm:px-6 py-6 sm:py-8 bg-transparent text-slate-100">
    <h1 class="text-xl sm:text-2xl lg:text-3xl font-bold select-none font-orbitron whitespace-nowrap">
      Nova Forge
    </h1>
    <nav class="hidden lg:flex gap-4 xl:gap-8 items-center">
      <a class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base transition-colors cursor-pointer" href="#about">
        Sobre Nós
      </a>
      <a class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base transition-colors cursor-pointer" href="#solutions">
        Soluções
      </a>
      <a class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base transition-colors cursor-pointer" href="#features">
        Diferenciais
      </a>
      <a class="text-slate-300 hover:text-slate-100 whitespace-nowrap text-sm xl:text-base transition-colors cursor-pointer" href="#cases">
        Cases
      </a>
      <button class="bg-blue-600 hover:bg-blue-500 text-white text-sm font-bold py-2 px-4 rounded transition-colors">
        Agendar Diagnóstico
      </button>
    </nav>

    <NavSocialGroup class="flex-shrink-0" />
  </header>
</template>