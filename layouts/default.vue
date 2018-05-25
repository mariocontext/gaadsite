<template>
  <div>
    <main-header/>
    <nuxt/>
    <main-sidebar/>
    <main-footer/>
  </div>

</template>

<script>
  
import MainHeader from '../components/general/MainHeader.vue'
import MainSidebar from '../components/general/MainSidebar.vue'
import MainFooter from '../components/general/MainFooter.vue'
  
export default {
  
  components: {
    MainHeader,
    MainSidebar,
    MainFooter
  }
  
}
  
</script>


<style>


</style>