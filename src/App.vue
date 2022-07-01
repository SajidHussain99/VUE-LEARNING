<template>
  <div id="app">
    <h1>Hello</h1>
    <!-- <LandingPage />
    <HelloWorld msg="hello world" /> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import LandingPage from './components/LandingPage.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    LandingPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0px;
  padding: 0px;
  height: 100vh;
  width: 100vw;
}
</style>
