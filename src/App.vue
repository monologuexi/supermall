<template>
  <div id="app">
  <router-view></router-view>
  <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from 'components/content/mainTabbar/MainTabBar'
export default {
  name: "App",
  components: {
    MainTabBar
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
