<template>
<!-- each component needs a single containing element and thus using span -->
  <span>
    <main-header/>

    <div class="main-content container">
      <main>

        <section class="general-content">
          <nuxt/>
        </section>

      </main>
    </div>

</span>

</template>

<script>
  
import MainHeader from '../components/general/MainHeader.vue'
import MainSidebar from '../components/general/MainSidebar.vue'
  
export default {
  
  components: {
    MainHeader,
    MainSidebar
  }
  
}
  
</script>


<style scoped>

</style>