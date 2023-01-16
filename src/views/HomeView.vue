<script setup>
import HeaderMain from '@/components/HeaderMain.vue'
import NavbarTop from '@/components/NavbarTop.vue'
import Handler from '@/components/Handler.vue'
import Carrusel from '@/components/Carrusel.vue'
import Carrusel2 from '@/components/Carrusel2.vue'
import Carrusel3 from '@/components/Carrusel3.vue'
import Carrusel4 from '@/components/Carrusel4.vue'
</script>

<script setup>
</script>

<template>
  <main>
    <img src="@/assets/cover.jpeg" alt="" class="cover__main">
    <HeaderMain />
    <NavbarTop />
    <Handler/>
    <Carrusel/>
    <Carrusel2/>
    <Carrusel3/>
    <Carrusel4/>
  </main>
</template>

<style scoped>
main {
  position: relative;
}
.cover__main {
  top: 0;
  left: 0;
  width: 375px;
  object-fit: cover;
}
</style>
