<template>
  <div class="bg-moonlight">
    <h4 class="py-4 uppercase bg-secondary text-center">My <span class="font-bold">Projects</span></h4>
    <div class="flex justify-center gap-20 py-20 text-primary bg-pattern">
      <div class="flex flex-col items-center justify-center">
        <img src="~assets/wf-peduli.png" alt="Peduli Lindungi Icon" class="w-80 rounded-3xl">
        <h6 class="font-semibold mt-4">SAVE.</h6>
        <h6>(App Design)</h6>
        <button class="btn mt-4">View</button>
      </div>
      <div class="flex flex-col items-center justify-center">
        <img src="~assets/wf-peduli.png" alt="Peduli Lindungi Icon" class="w-80 rounded-3xl">
        <h6 class="font-semibold mt-4">PeduliLindungi</h6>
        <h6>(UI App Design)</h6>
        <button class="btn mt-4">View</button>
      </div>
      <div class="flex flex-col items-center justify-center">
        <div class="w-80 h-80 overflow-hidden rounded-3xl">
          <img src="~assets/wf-ikea.png" alt="Peduli Lindungi Icon" class="ikea">
        </div>
        <h6 class="font-semibold mt-4">IKEA</h6>
        <h6>(UI Web Design)</h6>
        <button class="btn mt-4">View</button>
      </div>
      <div class="flex flex-col items-center justify-center">
        <div class="w-80 overflow-hidden rounded-3xl">
          <img src="~assets/wf-consina.png" alt="Peduli Lindungi Icon" class="w-full h-80 object-cover">
        </div>
        <h6 class="font-semibold mt-4">Consina</h6>
        <h6>(UI Web Design)</h6>
        <NuxtLink to="/consina">
          <button class="btn mt-4">View</button>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<style scoped>
.btn {
  @apply py-1 px-3 font-semibold;
}

.ikea {
  transform: scale(2.5) translateX(25%) translateY(30%);
}

.bg-pattern {
  background: url(~assets/pattern-transparent.svg) bottom center / 400px auto no-repeat;
}
</style>