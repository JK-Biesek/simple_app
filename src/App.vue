<template>
  <div id="app">
    <img  class="img_vue" src="./assets/logo.png">
    <skills msg="Welcome to Your Vue.js App"/>
  <router-view />
  </div>
</template>

<script>
import skills from './components/skills.vue'

export default {
  name: 'app',
  components: {
    skills
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');
body {
  background-color: #EEEEEE;
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
  padding-top: 30px;
}
#app > .img_vue{
  margin-left: 210px;
}
body, html {
  margin: 0;
  height: 100%;
}
#app {
    width: 50%;
}
</style>
