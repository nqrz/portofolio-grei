<template>
  <div class="bg-moonlight opacity-100">
    <div class="background h-screen opacity-30 overflow-hidden">
      <img src="~assets/pattern.png" alt="Pattern" class="opacity-50 h-56 absolute -left-20 top-1/4">
      <div class="pattern h-screen transform translate-x-20 -translate-y-44 opacity-50 flex items-end"></div>
    </div>
    <div class="absolute left-0 top-0 h-screen w-screen flex flex-col justify-center items-center text-primary">
      <div class="mt-64 mb-20">
        <h6 class="font-light">Hi, I'm</h6>
        <h1 class="text-9xl font-bold mb-4">Greialdy</h1>
        <h6 class="font-light text-right">Fitra Aliyaditama</h6>
      </div>
      <div>
        <button class="bg-secondary py-1 px-4 font-semibold text-black rounded">About</button>
        <button class="bg-secondary py-1 px-4 font-semibold text-black rounded ml-20">Contact</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.background {
  background: url(~assets/grei-transparent.png) #2F2443 bottom center no-repeat;
}

.pattern {
  background: url(~assets/pattern.png) bottom right / 342px 228px no-repeat;
}
</style>