<template>
  <div>
    <div class="absolute z-0 w-full h-96 overflow-hidden">
      <img src="~assets/wf-consina-2.png" alt="Wireframe Consina" class="w-full">
    </div>
    <div class="absolute z-10 bg-moonlight opacity-80 h-96 w-full"></div>
    <div class="absolute z-20 w-full">
      <NuxtLink to="/">
        <i class="fas fa-arrow-left text-primary mt-40 ml-40 text-4xl"></i>
      </NuxtLink>
      <div class="flex flex-col justify-center items-center text-secondary">
        <h4 class="text-center">Consina</h4>
        <h4 class="text-center pb-40">(UI Webdesign)</h4>
      </div>
    </div>
  </div>
</template>

<style scoped>
.zoom {
  transform: scale(2);
}
</style>