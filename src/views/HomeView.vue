<script setup>
import HeaderMain from '@/components/HeaderMain.vue'
import NavbarTop from '@/components/NavbarTop.vue'
</script>

<script setup>
</script>

<template>
  <main>
    <img src="@/assets/cover.jpeg" alt="" class="cover__main">
    <HeaderMain />
    <NavbarTop />
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
