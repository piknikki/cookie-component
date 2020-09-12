<template>
  <div id="app">
    <div id="container" class="box">
      <div class="content">We use cookies to ensure you get the best experience on our website.</div>
      <a href="#">Our privacy policy</a>
      <br>
      <button class="button is-warning"> 🍪 NomNomNom!! </button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}

#container {
  margin: 0 auto;
  background-image: url("./assets/CM1.png");
  background-size: contain;
  background-repeat: no-repeat;
  width: 500px;
  height: auto;
  background-color: #13B0EF;
}

a {
  color: white;
  border-bottom: 6px solid lightseagreen;
  margin: 10px;
}

.content {
  color: white;
  width: 50%;
  margin: 10px;
}

button {
  margin: 15px 10px 5px;
}
</style>
