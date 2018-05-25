<template>
  <div>
    <my-special-area/>
    <p class="interesting">Hi from About</p>
    
    <div class="columns">
      <div class="column">
        First column
      </div>
      <div class="column">
        Second column
      </div>
      <div class="column">
        Third column
      </div>
      <div class="column">
        Fourth column
      </div>
    </div>

    
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
  
  $my-cool-color: #F00;

  .interesting {
     color: $my-cool-color; 
  }
  
</style>