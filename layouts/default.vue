<template>
<!-- each component needs a single containing element and thus using span -->
  <span>
    <main-header/>

    <div class="main-content container">
      <main class="columns is-variable is-5">

        <section class="column general-content">
          <nuxt/>
        </section>

        <aside class="column is-one-quarter secondary-content" role="complementary">
          <main-sidebar/>
        </aside>
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