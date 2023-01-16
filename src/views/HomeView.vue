<script setup>
import HeaderMain from '@/components/HeaderMain.vue'
import NavbarTop from '@/components/NavbarTop.vue'
</script>

<script setup>
</script>

<template>
  <main>
    <img src="@/assets/cover.png" alt="" class="cover__main">
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
}
</style>
