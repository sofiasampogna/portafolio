<script setup>
import SocialMedia from '../components/SocialMedia.vue'
</script>

<template>
    <SocialMedia />
    <div id="wrapper">
    <div class="about">
      <h5>About Me</h5><br>
    </div>
    <div class="desc">
      <h2>Computer scientist in training. Special interest in research regarding interdependence between computer science and cognitive science, and the use of technology in the Finance Sector.</h2>
    </div>
    <br>
    <br>
    <div>
        <h2>Skills and Relevant Knowledge:</h2>
        <ul>
          <li>Programming Languages: C++, Python, R, Java, Swift</li>
          <li>Web Development: HTML/CSS, JavaScript, React, Angular, Vue and Selenium</li>
          <li>Database Management: SQL Development, Internet of Things (IoT) knowledge</li>
          <li>Other Relevant Experience: Data Structures, Algorithm Design, Software Design Methodology, and Technical Writing</li>
        </ul>
    </div>
  </div>
  <img src="../assets/icons/profile.jpg" class="profile">
</template>


<style>
@media (min-width: 1024px) {
  .about {
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
  top: 00px;
}

h2 {
  font-family: sans-serif;
  font-size: 30px;
  line-height: 1.2em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  left: 70px;
  top: -200px;
}

ul {
  font-family: sans-serif;
  font-size: 20px;
  line-height: 1.2em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  left: 0px;
  top: 120px;
}

li {
  font-family: sans-serif;
  font-size: 20px;
  line-height: 1.2em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  left: 70px;
  top: -300px;
}


.profile {
    width: 30%;
    height: fit-content;
    margin-top: 0%;
    margin-left: 10%;
    top: 0%;
    bottom: 0%;
    left: auto;
    right: 0%;
}

</style>
