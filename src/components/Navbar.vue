<template>
  <nav class="navbar navbar-expand-sm navbar-light bg-light mb-2">
      <!-- <div class="container"> -->
          <span class="navbar-brand">Essentials</span>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
          </button>
          <div class="navbar-collapse d-flex justify-content-end" id="navbarSupportedContent">
            <ul class="navbar-nav">
              <li class="nav-item">
                <router-link class="nav-link" to="/">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/about">About</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link" to="/contact">Contact</router-link>
              </li>
              <li class="nav-item mx-2">
                <router-link class="btn btn-outline-success" to="/login">Login</router-link>
              </li>
              <li class="nav-item">
                <router-link class="btn btn-success" to="/register">Register</router-link>
              </li>
              <li class="nav-item" v-if="false">
                <button class="btn btn-danger">Logout</button>
              </li>
            </ul>
          </div>
      <!-- </div> -->
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>