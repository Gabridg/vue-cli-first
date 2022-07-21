<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
  </div>
</template>

<script>
import TitleComponents from './components/Header.vue';
import HeroComponents from './components/Main.vue';



export default {
  name: 'App',
  components: {
    Header: TitleComponents,
    Main: HeroComponents,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif;
  margin-top: 60px;
}
</style>
