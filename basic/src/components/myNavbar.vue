<template>
  <div class="navbar">
    <img class="logo" src="../assets/logo.png">
    <div class="bar">
        <span class="item" v-for="nav in navs" :key="nav.id">{{nav.text}}</span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      navs:[
        {id:1, text: "Work"},
        {id:2, text: "Bio"},
        {id:3, text: "Home"}
      ]
    }
  },
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
}
.navbar {
    width: 100%;
    display: flex;
    flex-direction: row;
    height: 80px;
    background-color: #fff;
    border-bottom: 1px solid #000;
}
.logo {
    width: 20%;
    /* background-color: #666; */
    float: left;
    margin-left: 70px;
}
.bar {
    color: #000;
    width: 80%;
    /* background-color: #444; */
    margin-right: 70px;
}
.item {
  margin: 30px;
  /* background-color: green; */
  float: right;
  font-size:1.5em;
  font-family: Helvetica, 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
</style>