<script setup>
import SocialMedia from '../components/SocialMedia.vue'
</script>

<template>
    <SocialMedia />
    <div id="wrapper">
    <div class="experience">
      <h5>Experience</h5><br>
    </div>
    <div class="desc">
      <h2>Computer scientist in training. Special interest in research regarding interdependence between computer science and cognitive science, and the use of technology in the Finance Sector.</h2>
    </div>
    <div>
        <h2>Work Experience:</h2>
        <ul>
          <li>Software Development Intern, Microsoft. Redmond, Washington. June 2023 - August 2023 (anticipated). </li>
          <li>Software Development Intern, Intel. Guadalajara, Jalisco. August 2022 - May 2023</li>
          <li>Software Quality Tester Intern, Epicor, Monterrey, México, December 2021 – June 2022</li>
          <li>Oracle EDI Support Intern, Schneider Electric, Monterrey, México, July 2021 – January 2022</li>
          <li>Software Team Leader Intern, Tecnológico de Monterrey, Monterrey, México, January 2021 – August 2021</li>
        </ul>
    </div>
  </div>
</template>


<style>
@media (min-width: 1024px) {
  .experience {
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

</style>
