<template>
  <div>
    <h1>Welcome!</h1>
    
    <div class="columns is-3">
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
    
    <!-- examples from https://vuejs.org/v2/guide/index.html to see if Vue in glitch is working properly It sometimes works and sometimes spits out a compilation error. Something is wrong with either the Nuxt install or Glitch or both. -->
    
    <span v-bind:title="message">
    Hover your mouse over me for a few seconds
    to see my dynamically bound title!
    </span>
    
    
    <div>
      <span v-if="seen">Now you see me</span>
    </div>
    
   <div id="app-7">
  <ol>
    <!--
      Now we provide each todo-item with the todo object
      it's representing, so that its content can be dynamic.
      We also need to provide each component with a "key",
      which will be explained later.
    -->
    <li
      v-for="todo in todos"
      v-bind:todo="todo"
      v-bind:key="todo.id">
      {{todo.text}}
    </li>
  </ol>
</div>
  
    
  </div>
</template>

<script>
  
  module.exports = {
   
    data:function() {
    
      return {
        message: 'hello from data!',
        seen: true,
        todos: [
          { id:1, text: 'Learn JavaScript' },
          { id: 2, text: 'Learn Vue' },
          { id: 3, text: 'Build something awesome' }
        ]
        
      }
    }
    
  }

</script>

<style scoped>

  .column {
    background-color: #F90;
    border: 1px #333 solid;
  }
  
</style>
