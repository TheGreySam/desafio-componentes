<template>

<div id="Morty">
  <h2>Lista de personajes de Rick and Morty</h2>
  <hr>

  <div>
    <PersonajesMorty/>
    
    
  </div>
  
            
        </div>
  
</template>

<script>

import PersonajesMorty from './components/mortyImages.vue'
//import image from './components/mortyImages.vue'

export default {
  name: 'App',
  components: {
    PersonajesMorty,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: greenyellow;
  margin-top: 60px;
}
body {
    background-image: url(https://rickandmortypod.com/wp-content/uploads/2018/11/cropped-RM_page-header_background1-3.png);
    z-index: 0;
    color: greenyellow;
};
</style>
