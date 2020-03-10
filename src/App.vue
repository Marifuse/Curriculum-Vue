<template>
  <div id="app">
    <img alt="Sakura-logo" src="./assets/sakura-logo.png">
    <Personal titulo="Curriculum Personal"/>
    <Profesional/>
    <Curso/>
    <link href="https://fonts.googleapis.com/css?family=Caveat:400,700&display=swap" rel="stylesheet">
  </div>
</template>

<script>
import Personal from './components/Personal.vue'
import Profesional from './components/Profesional.vue'
import Curso from './components/Curso.vue'

export default {
  name: 'App',
  components: {
    Personal,
    Profesional,
    Curso
  }
}
</script>

<style>
body {
  margin: 0;
  background-image: url(./assets/fondo-sakura.png);
  background-size: cover;
  background-repeat: no-repeat;
}
#app {
  font-family: 'Caveat', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 1em;
}
h1 {
  color: black;
  text-decoration: underline;
  margin-bottom: 2em;
}
img {
  width: 30%;
  border-radius: 50%;
  margin-bottom: 2em;
}
</style>
