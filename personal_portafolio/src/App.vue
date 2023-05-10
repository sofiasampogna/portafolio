<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Introduction from './components/Introduction.vue'
import SocialMedia from './components/SocialMedia.vue'
</script>

<template>
  <SocialMedia />
  <header>
    <div class="wrapper">
      <Introduction msg="SOFIA SAMPOGNA MONTEMAYOR" />
    </div>
  <RouterView />
</header>
</template>

<style scoped>
.wrapper {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
