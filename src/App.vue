<template>
  <div id="app">
    <!-- <navbar/> -->
    <img id="logo" src="./assets/logo.png">
    <div class="container">
      <titulo/>
      <subtitulo/>
      <blocos/>
      <blocos/>
    </div>
  </div>
</template>

<script>
  import navbar from './components/navbar.vue'
  import titulo from './components/titulo.vue'
  import subtitulo from './components/subtitulo.vue'
  import blocos from './components/texto.vue'

  export default {
    name: 'app',
    components: {
      navbar,
      subtitulo,
      titulo,
      blocos
    },
    data: {
      
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 11vh;
  }

  .container>*{
    margin-top:5vh;
  }

  #logo{
    height: 30vh
  }
</style>
