<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
  <section id="home">
    <div
      class="col-md-12 justify-content-center align-items-center text-center"
    >
      <div class="col-md-12 mx-auto">
        <router-link to="/"
          ><img src="@/assets/img/ash-pikachu.png" alt="Ash and Pikachu"
        /></router-link>
      </div>
      <div class="col-md-12 mx-auto">
        <router-link
          to="/list"
          class="btn btn-danger text-uppercase font-weight-bold text-decoration-none"
          >pokebola, vai!</router-link
        >
      </div>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "MainPage",
};
</script>

<style lang="scss" scoped>
@import "@/assets/sass/style.scss";
</style>
