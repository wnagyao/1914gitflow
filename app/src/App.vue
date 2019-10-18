<template>
  <div id="app">
    这里是1914git测试
    <Login></Login>
    <Reg></Reg>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from './components/Login.vue'
import Reg from './components/reg.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    Login,
    Reg
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
