<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <My_Title></My_Title>
    <My_Hero></My_Hero>
  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
} */
import My_Title from './components/My_Title.vue'
import My_Hero from './components/My_Hero.vue'

export default {
  name: 'App',
  components: {
    My_Title, 
    My_Hero
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
</style>
