<template>
  <div id="app">
    <MainCard/>
    <ProjectsCard/>
    <footer>
      <span>© 2024 Joshua Pino - BSIT 3C</span>
    </footer>
  </div>
</template>

<script>
import MainCard from './components/MainCard.vue'
import ProjectsCard from './components/ProjectsCard.vue'

export default {
  name: 'App',
  components: {
    MainCard,    
    ProjectsCard
  }
}
</script>

<style>
@font-face {
    font-family: 'Product Sans';
    src: url('../fonts/ProductSans-Regular.ttf') format('truetype');
}

body {
  margin: 0;
  background-color: #0a192f !important;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

footer {
  background-color: #333333;
  padding: 20px 0;
}

footer span {
  color: #fff;
  font-size: 12px; /* Adjust font size as needed */
}
</style>
