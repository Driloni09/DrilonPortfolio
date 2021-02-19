<template>
  <div id="app">
    <navigation/> 
    <lander/>
    <studies/>
    <portfolio/>
    <projects/>
    <contact/>
    <Footer/>
  </div>
</template>

<script>
import Navigation from './components/Includes/Navigation.vue' 
import Lander from './components/Lander.vue'
import Portfolio from './components/Portfolio.vue'
import Contact from './components/Includes/Contact.vue'
import Footer from './components/Includes/Footer.vue'
import Studies from './components/Studies.vue'
import Projects from './components/Portfolio/Projects.vue'

export default {
  name: 'App',
  components: {
    Navigation,  //instantiate it here
    Lander,
    Portfolio,
    Contact,
    Footer,
    Studies,
    Projects
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
