<template>
<div id="nav">
<router-link to="/">Home</router-link> |
<router-link to="/about">About</router-link> |
<router-link to="/contact">Contact</router-link>
</div>
 <router-view></router-view>
</template>

<script>


export default {
  name: 'App',
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#nav {
  padding: 30px;
  margin: 10px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  font-family: "poppins bold";
}

#nav a.router-link-exact-active {
  color: rgb(248, 116, 116);
}
</style>
