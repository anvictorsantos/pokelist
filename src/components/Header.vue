<template>
    <header>
        <nav class="navbar">
        <a class="navbar-brand mx-auto img-fluid" href="/">
          <img src="@/assets/img/logo.png" alt="Pokemon" height="94" width="256">
        </a>
        </nav>
    </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>


<style>

</style>