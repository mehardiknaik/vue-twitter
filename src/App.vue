<template>
  <TopBar />
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <div class="container">
    <LeftContainer />
    <CenterContainer />
    <RightContainer />
  </div>
</template>

<script>
import TopBar from './components/TopBar.vue';
import LeftContainer from "./components/LeftContainer.vue"
import CenterContainer from "./components/CenterContainer.vue"
import RightContainer from "./components/RightContainer.vue"

export default {
  name: 'App',
  components: {
    TopBar,
    LeftContainer,
    CenterContainer,
    RightContainer,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}

body {
  margin: 0;
  padding: 0;
}

.container {
  display: grid;
  grid-template-columns: 1fr 60% 1fr;
  margin-inline:1rem;
  margin-top: 3px;
}
</style>
