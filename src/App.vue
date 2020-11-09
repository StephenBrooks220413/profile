<template>
  <div id="app">
    <Nav/>
    <HelloWorld/>
    <br><br><br><br><br><br>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    Nav,
    HelloWorld
  }
}
</script>

<style>
@import './assets/bootstrap.min.css';
#app {
  padding: 0;
  margin: 0;
}
</style>
