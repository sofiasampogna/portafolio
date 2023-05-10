<script setup>
import MainMenu from '../components/MainMenu.vue'
import { RouterLink, RouterView } from 'vue-router'
import Introduction from '../components/Introduction.vue'
import SocialMedia from '../components/SocialMedia.vue'
</script>

<template>
    <SocialMedia />
  <header>
    <div class="wrapper">
      <Introduction msg="SOFIA SAMPOGNA MONTEMAYOR" />
    </div>
  <RouterView />
</header>
  <main>
    <MainMenu />
  </main>
</template>
