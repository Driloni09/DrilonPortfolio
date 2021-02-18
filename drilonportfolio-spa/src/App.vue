<template>
  <div id="app">
    <navigation/> 
    <lander/>
    <portfolio/>
    <contact/>
  </div>
</template>

<script>
import Navigation from './components/Includes/Navigation.vue' //import the component
import Lander from './components/Lander.vue'
import Portfolio from './components/Portfolio.vue'
import Contact from './components/Includes/Contact.vue'

export default {
  name: 'App',
  components: {
    Navigation,  //instantiate it here
    Lander,
    Portfolio,
    Contact
  }
}


</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
 
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
