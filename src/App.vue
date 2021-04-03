<template>
  <div id="app">
    <!-- Top bar section BEGIN -->
    <div class="mb-5">
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="#">I-Visit</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

          <b-button-group>
            <b-button variant="success">
              <router-link to="/">Home</router-link>
            </b-button>
            <b-button variant="warning">
              <router-link to="/about">About</router-link>
            </b-button>
          </b-button-group>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-button variant="success">Profile</b-button>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <!-- Top bar section END -->

    <!-- Content BEGIN -->
    <router-view/>
    <!-- Content END -->

    <!-- Bottom bar section BEGIN -->
    <div>Copyright © 2021 I-Visit. A Corporation Company for islands to visit. All rights reserved.</div>
    <!-- Bottom bar section END -->
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
