<template>
  <div id="nav">
    <router-link class="link" to="/">Home</router-link>
    <router-link class="link" to="/about">About</router-link>
    <router-link class="link" to="/user">User</router-link>
  </div>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
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
.link {
  margin-right: 15px;
}
</style>
