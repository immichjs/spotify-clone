<template>
  <div id="app">
    <Header/>
    <Main/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap');
  
  * {
    margin: 0;
    padding: 0;
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
    font-family: 'Montserrat', Helvetica, Arial, sans-serif;
  }
</style>
