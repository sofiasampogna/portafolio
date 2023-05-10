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
    <h2 class="white">{{ msg }}</h2> <br>
    <h4>
      Computer science student with a <br> keen interest in the intersection of <br> technology and finance. <br><br> Currently working as an Undergraduate Software Engineer at Intel Mexico. 
    </h4>
  </div>
</template>

<style scoped>
h2 {
  margin-left: 20%;
  text-align: left;
  letter-spacing: 4px;
  text-transform: uppercase;
  margin-top: 30%;
  margin-bottom: 0;
  line-height: 1.1em;
  position: relative;
  font-family: sans-serif;
  font-size: 18px;
  font-weight: 500;
  width: 50%;
  top: 100px;
  left: 30px;

}

h4 {
  margin-left: 20%;
  margin-right: 0;
  font-family: sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 1.1em;
  position: relative;
  width: 90%;
  top: 100px;
  left: 30px;
  

}

.greetings h1,
.greetings h3 {
  text-align: left;
  top: 100px;
  font-family: sans-serif;
}

</style>
