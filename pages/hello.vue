<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Hello
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
        <router-link 
          to="/"
          class="button is-primary is-rounded my-class-two"
        >Home</router-link>
    </div>

       <div class="columns is-variable is-3">
          <div class="column">
             <div class="red">1</div>
          </div>
          <div class="column">
             <div class="green">1</div>
          </div>
          <div class="column">
             <div class="red">1</div>
          </div>
          <div class="column">
             <div class="green">1</div>
          </div>
        </div>


  </section>

</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style scoped lang="scss">

$my-special-color: #DDD;
</style>
