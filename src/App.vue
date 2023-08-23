<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Header from './components/Header.vue'
</script>
<script>
  export default {
    data() {
      return {
        title: 'My test To Do App'
      }
    }
  }
</script>

<template>
  <header>
    <Header></Header>
  </header>

  <main>
    
  </main>
</template>

<style scoped>
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
}

header {
  position: fixed;
  top: 0px;
  width: 100%;
  margin: 0 auto;
  left: 0px;
  height: 100px;
  background-color: #05a8aa;
}



@media (min-width: 1024px) {
  header {
    
    
  }


  
}
</style>
