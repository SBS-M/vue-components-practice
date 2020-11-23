<template>
  <center>
    <img alt="Vue logo" src="./assets/logo.png">
    <AppContador/> <AppContador/> <AppContador/> <AppContador/>
    
    <h2>Listado de planes de cursos de programacion</h2>

    
      <!-- <div class="plan">
        <div class="descripcion">
          <span>Plan 1 - Principiante</span>
        </div>
      </div>
      <div class="plan">
        <div class="descripcion">
          <span>Plan 2 - Intermedio</span>
        </div>
      </div>
      <div class="plan">
        <div class="descripcion">
          <span>Plan 3 - Avanzado</span>
        </div>
      </div> 
      <plan nombre="Plan 1 - Principiante"/>
      <plan nombre="Plan 2 - Intermedio"/>
      <plan nombre="Plan 3 - Avanzado"/>
      <plan nombre="Plan 4 - Hackers"/>
      -->
      
      <planes/>
      

  </center>  
</template>

<script>
/* <HelloWorld msg="Welcome to Your Vue.js App"/>
import HelloWorld from './components/HelloWorld.vue' */
import AppContador from './components/Contador'
import Planes from './components/Planes'

export default {
  name: 'App',
  components: {
    AppContador,
    Planes
  },
  data() {
    return {
      
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

</style>
