<template>
  <div class="navigation">
    <div class="container">
      <nav class="navbar navbar-expand-md" >
        <a class="navbar-brand" >
          <img 
            class="logoImg" 
            src="~/assets/logo.png"
          >
        </a>
        <button class="navbar-toggler">
          <span class="navbar-toggler-icon"/>
        </button>
        <div class="collapse navbar-collapse" >
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" >
                <nuxt-link to="/">
                  Home
                </nuxt-link>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" >
                <nuxt-link to="/about">
                  About
                </nuxt-link>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" >
                <nuxt-link to="/contact">
                  Contact
                </nuxt-link>
              </a>
            </li> 
          </ul>
        </div> 
      </nav>
    </div>
  </div>
</template>

<script>
import Logo from './Logo.vue';

export default {
  components: {
    Logo
  }
}
</script>

<style>
  .navigation {
    width: 100vw;
    border-bottom: 2px solid #eee;
  }

  .logoImg {
    height: 40px;
  }
</style>
