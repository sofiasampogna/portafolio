<script setup>
import SocialMedia from '../components/SocialMedia.vue'
</script>

<template>
    <SocialMedia />
    <div id="wrapper">
    <div class="contact">
      <h5>TO DO</h5><br>
    </div>
    <div class="desc">
      <h2>Contact Info.</h2>
    </div>
  </div>
</template>


<style>
@media (min-width: 1024px) {
  .contact {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

h5 {
  font-family: 'oregon_ldo_bookregular';
  letter-spacing: 0.1em;
  text-align: left;
  text-transform: uppercase;
  font-size: 10.5vw;
  font-weight: 300;
  line-height: .85em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  left: 70px;
  top: -100px;
}

h2 {
  font-family: sans-serif;
  font-size: 30px;
  line-height: 1.2em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  left: 70px;
  top: -300px;
}

</style>
