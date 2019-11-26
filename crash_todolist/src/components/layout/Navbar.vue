<template>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">NavBar</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>
          <router-link to="/">
            <p>Home</p>
          </router-link>
        </b-nav-item>
        <b-nav-item>
          <router-link to="/about">
            <p>About</p>
          </router-link>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
<script>
export default {
    name: "Navbar"
}
</script>

<style scoped>
p {
    color: #fff;
    text-decoration: none;
    margin: 0;
}
</style>