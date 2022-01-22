<script setup>
import myNavbar from "./myNavbar.vue";
import myFooter from "./myFooter.vue";
</script>

<template>
  <div>
      <MyNavbar />
      <img src="../assets/photo.JPG" class="photo">
      <MyFooter />
  </div>
  
</template>

<script>
export default {
  
    components:{
        myNavbar,
        myFooter
    }
}
</script>

<style scoped>
.photo{
  width: 50%;
  display: flex;
  margin: 30px auto;
}

</style>