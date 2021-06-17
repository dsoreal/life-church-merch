<template>
<img class="header-img" src="./assets/topPage.png" alt="">
  <navbar />
  <item />
  <router-view/>
</template>
  <script>
    import navbar from './components/nav.vue'
    import item from './components/item.vue'

    export default {
      components: {navbar, item}
    }
  </script>
  
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.header-img {
  padding-right: 60px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

