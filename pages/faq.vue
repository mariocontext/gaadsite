<template>
  <div>
    <my-special-area/>
    <p class="interesting">Hi from About</p>
    <router-link to="/">Home page</router-link>
  </div>
</template>


<script>
  
import MySpecialArea from '../components/MySpecialArea.vue'
  
export default {
  
    components: {
     MySpecialArea
    }
  
}
</script>

<style scoped lang="scss">

  
</style>