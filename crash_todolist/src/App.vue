<template>
  <div id="app">
    <Navbar />
    <Header />
    <div class="test">
      <p>{{message}}</p>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Navbar from "./components/layout/Navbar"
import Header from "./components/layout/Header"
export default {
  name: "app",
  components: {
    Header,
    Navbar
  },
  data() {
    return {
      titleUrl: this.$route.name,
    };
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.test {
  color: #000;
}
</style>
