<template>
  <section>
    <Header/>
    <div class="container">
      <div class="row justify-content-center mt-4">
        <logo/>
        <h3 class="mt-5">
          Vue-Nuxt-Bootstrap4 Project
        </h3>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Header from '~/components/Header.vue'

export default {
  components: {
    Logo,
    Header
  }
}
</script>

<style>

</style>
