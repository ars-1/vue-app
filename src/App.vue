<template>
<img alt="Vue logo" src="./assets/logo.png" height="50" />
    <h1 class="heading">Vue.js</h1>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
  </div>
  <router-view />
  <app-footer />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.heading,
  img {
    float: left;
    padding: 10px;
  }
  .heading {
    margin-top: 5px;
    padding-left: 0;
  }

#nav {
  padding: 30px;
  margin-right: 10%;

  a {
    margin-top: 3px;
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
<script>
import AppFooter from '@/components/AppFooter.vue'

export default {
  components: {
    AppFooter
  }
}
</script>
