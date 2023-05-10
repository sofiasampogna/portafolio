<script setup>
import SocialMedia from '../components/SocialMedia.vue'
</script>

<template>
    <SocialMedia />
    <div class="experience">
      <h5>Work Experience</h5><br>
    </div>
    <div class="list">
        <ul>
          <li>
            <h1> Microsoft</h1>
                <h3>Software Development Intern</h3> 
          </li>
          <li>
            <h1>Intel</h1>
                <h3>Software Development Intern</h3> 
          </li>
          <li>
            <h1>Epicor Software</h1>
                <h3>Software Quality Tester Intern</h3>
          </li>
          <li>
            <h1>Schneider Electric</h1>
                <h3>Oracle EDI Support Intern</h3>
          </li>
          <li>
            <h1>Campus City</h1>
                <h3>Software Team Leader Intern</h3>
            </li>
            <li>
            <h1>NY Institute of Finance</h1>
                <h3>Mastery Certification in Wealth Management Training Program</h3>
            </li>
        </ul>
    </div>
</template>


<style>
@media (min-width: 1024px) {
  .experience {
    min-height: 100vh;
    width: 30%;
    display: flex;
    align-items: center;
    right: 80px;
    top: 280px
   
  }
}

.list{
    width: 900px;
    margin: 2px;

}

h5 {
  font-family: 'oregon_ldo_bookregular';
  letter-spacing: 0.1em;
  text-align: left;
  text-transform: uppercase;
  font-size: 80px;
  line-height: .85em;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  transition: all 0.3s ease-in-out;
  top: -100px;
  color: #393428;
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

h3 {
  font-family: sans-serif;
  font-size: 15px;
  line-height: 1.2em;
  text-transform: uppercase;
  text-decoration: none;
  display: block;
  margin-left: 10%;

}

ul {
  height: 90%;
  flex-direction: column;
  display: flex;
  list-style-type: none;  
}

h1{
font-family: 'oregon_ldo_bookregular';
  letter-spacing: 0.1em;
  text-align: left;
  text-transform: uppercase;
  font-size: 65px;
  font-weight: 300;
  line-height: .90em;
  text-decoration: none;
  transition: transform .3s ease-in-out, color .3s ease-in-out, font-size .3s ease-in-out;
  display: block;
  transition: all 0.3s ease-in-out;
  margin-top: 2%;
}

</style>
