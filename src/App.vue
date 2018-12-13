<template>
  <div id="app">
    <navbar/>
    <img id="logo" src="./assets/logo.png">
    <div class="container">
      <titulo/>
      <subtitulo/>
      <h1 id="binding">{{ message }}</h1>
      <blocos/>
      <blocos/>
    </div>
    <parallax/>
    <div class="container">
      <imagemetexto/>
      <imagemetextoinvertido/>
    </div>
  </div>
</template>

<script>
  import navbar from './components/navbar.vue'
  import titulo from './components/titulo.vue'
  import subtitulo from './components/subtitulo.vue'
  import blocos from './components/texto.vue'
  import parallax from './components/parallax.vue'
  import imagemetexto from './components/imagemetexto.vue'
  import imagemetextoinvertido from './components/imagemetextoinvertido.vue'

  export default {
    name: 'app',
    components: {
      navbar,
      subtitulo,
      titulo,
      blocos,
      parallax,
      imagemetexto,
      imagemetextoinvertido
    },

    data: {
      message: "exemplo"
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
