<template>
  <div id="app">
    <nav>
      <router-link id="Home1" to="/">Abraça São Paulo</router-link> 
      <router-link id="video" to="/about">Doador</router-link> 
      <router-link id="imagem" :to="{name: 'NovoArquivo'}">Beneficiário</router-link>
    </nav>
    <router-view/>
  </div>
</template>
<script>
  export default{

  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #B8860b;
}
</style>
