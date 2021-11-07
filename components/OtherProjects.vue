<template>
  <div>
    <h4 class="pt-20 pb-10 uppercase text-secondary text-center">Other <span class="font-bold">Projects</span></h4>
    <div class="layout overflow-hidden">
      <img src="~assets/logo-anugrah.png" alt="Logo Lomba Anugrah Medika" class="w-1/3 hover:shadow-lg logo anugrah">
      <img src="~assets/logo-greifood.png" alt="Logo Mie Letus Greifood" class="w-1/3 hover:shadow-lg logo greifood">
      <img src="~assets/logo-youmanis.png" alt="Logo Youmanis Drink" class="w-1/3 hover:shadow-lg logo youmanis">
      <img src="~assets/logo-unlimited.png" alt="Logo Unlimited" class="w-1/2 hover:shadow-lg logo unlimited">
      <img src="~assets/logo-warjam.png" alt="Logo Warung Jam'iyyah" class="w-1/2 hover:shadow-lg logo warjam">
    </div>
  </div>
</template>

<style scoped>
.layout {
  display: grid;
  grid-template-columns: 1.2fr 0.9fr 0.9fr;
  grid-template-rows: 1.2fr 0.3fr 1.5fr;
  gap: 0px 0px;
  grid-auto-flow: row;
  grid-template-areas:
    "anugrah greifood youmanis"
    "anugrah warjam warjam"
    "unlimited warjam warjam";
}

.anugrah { grid-area: anugrah; }

.greifood { grid-area: greifood; }

.youmanis { grid-area: youmanis; }

.warjam { grid-area: warjam; }

.unlimited { grid-area: unlimited; }

.logo {
  object-fit: cover;
  width: 100%;
  height: 100%;
  transition: 0.2s ease-in-out all;
}

.logo:hover {
  transform: scale(1.01);
  cursor: pointer;
}
</style>