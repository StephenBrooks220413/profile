<template>
  <div id="app">
    <Nav/>
    <HelloWorld/>
    <br><br><br><br><br><br>
    <Info/>
    <br><br><br><br><br><br>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import HelloWorld from './components/HelloWorld.vue'
import Info from './components/Info.vue'

export default {
  name: 'App',
  components: {
    Nav,
    HelloWorld,
    Info
  }
}
</script>

<style>
@import './assets/bootstrap.min.css';
#app {
  padding: 0;
  margin: 0;
}
.footer {
  line-height: 40px;
  padding-top: 20px;
  padding-bottom: 30px;
  text-align: center;
  background-color:white;
  height: 100%;
}
</style>
