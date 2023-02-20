<template>
  <Home />
  <About />
  <Footer />
</template>

<script>

import Home from './components/Home.vue'
import About from './components/About.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Home,
    About,
    Footer
  }
}
</script>
