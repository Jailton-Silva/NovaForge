<script setup lang="ts">
</script>

<template>
  <NuxtLayout>
    <div class="flex flex-col items-center justify-center relative z-10 py-12">
      <h1
        class="mx-auto mt-4 text-center text-4xl font-bold bg-gradient-to-r from-sky-400 via-slate-300 to-sky-200 bg-clip-text text-transparent"
      >
      Forjando tecnologia que
      <br />impulsiona negócios.
      </h1>
      <span class="block mt-4 mx-auto text-center text-3xl font-bold text-slate-100">
        Nova Forge
      </span>

      <p class="block mt-4 mx-auto text-center text-base text-slate-300">
        Transformamos desafios em software robusto,
        <br />
        escalável e preparado para crescer junto com você.
      </p>

      <div class="grid grid-cols-2 mt-10 gap-4 max-w-md w-full mx-auto">
			<button
				class="bg-transparent border border-blue-500 text-blue-300 hover:bg-blue-500/20 hover:text-white font-bold py-2 px-4 rounded transition-colors"
			>
				Projetos
			</button>
			<button
          class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded transition-colors"
        >
				Contate-nos
			</button>
		</div>
    </div>
  </NuxtLayout>
</template>