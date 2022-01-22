<script setup>
import Home from "./components/Home.vue";
</script>

<template>
  <div id="app">
      <Home />
  </div>
</template>

<script>

export default{
  components: {
    Home,
  }
}
</script>

<style>
/* @import './assets/base.css'; */
.photo{
  width: 50%;
  display: flex;
  margin: 30px auto;
}

</style>
