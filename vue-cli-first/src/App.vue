<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld/>
    <Hero/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import Hero from '@/components/Hero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Hero,
  }
}
</script>

<style>
/** Generals */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  }
  
</style>
