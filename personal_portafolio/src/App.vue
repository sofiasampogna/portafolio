<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Introduction from './components/Introduction.vue'
import SocialMedia from './components/SocialMedia.vue'
</script>

<template>
  <header>
    <div class="wrapper">
    </div>
  <RouterView />
</header>
</template>

<style scoped>
.wrapper {
  width: 10%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
