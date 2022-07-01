<template>
  <div id="app">
    <!-- <LandingPage /> -->
    <MainMenu />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import LandingPage from './components/LandingPage.vue';
import MainMenu from './components/MainMenu.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    LandingPage,
    MainMenu,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding: 0px;
  margin: 0px;
  width: 100%;
}
</style>
