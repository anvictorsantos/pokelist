<template>
  <nav class="navbar">
    <a class="navbar-brand mx-auto img-fluid" href="/">
      <img src="@/assets/img/logo.png" alt="Pokemon" height="94" width="256" />
    </a>
  </nav>
</template>

<script>
export default {
  name: "HeaderComponent",
  props: {
    msg: String,
  },
};
</script>

<style></style>
