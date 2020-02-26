<template>
  <div id="app">
    <Header msg="Welcome to Your Vue.js App"/>   
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
#app {
  background: linear-gradient(180deg, rgba(2,0,36,1) 0%, rgba(255,0,0,1) 0%, rgba(255,0,0,1) 50%, rgba(255,255,255,1) 50%);
  font-family: 'Acme';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  height: 100vh;
  margin: 0;
  padding: 0;    
}
</style>
