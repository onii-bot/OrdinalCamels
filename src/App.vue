<template>
  <Home />
  <About />
</template>

<script>

import Home from './components/Home.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Home,
    About
  }
}
</script>
