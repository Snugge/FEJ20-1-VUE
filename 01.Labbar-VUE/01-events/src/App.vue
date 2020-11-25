<template>
  <div id="app">
    <Navbar />
    <Hero btnText="Klicka Här!"/>
    <Footer />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar'
import Hero from './components/Hero'
import Footer from './components/Footer'


export default {
  name: 'App',
  data() {
    return {
      
    }
  },
  props: {

  },
  components: {
    Navbar,
    Hero,
    Footer,
    
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

* {
  margin: 0;
  padding: 0;
}
</style>
