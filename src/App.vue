<template>
  <div id="app">
  </div>
</template>

<script>
import HelloWorldVue from './components/HelloWorld.vue';



export default {
  name: 'App',
  components: {
    Header: Title,
    Main: HelloWorldVue,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif;
  margin-top: 60px;
}
</style>
