<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="white">{{ msg }}</h1> <br>
    <h3>
      Computer science student with a keen interest in the intersection of technology and finance. With my experience in software development, quality testing, and database management, I am confident in my ability to contribute to the team and gain valuable insights into the financial industry.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-size: 2rem;
}

h3 {
  font-size: 1.5rem;
}

.greetings h1,
.greetings h3 {
  text-align: left;
  top: 100px;
  font-family: sans-serif;
}

</style>
