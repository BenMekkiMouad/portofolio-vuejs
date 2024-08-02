<template>
  
  <HeaderComponent/>
  <HeroComponent/>


</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import HeroComponent from './components/HeroComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    HeroComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
</style>
