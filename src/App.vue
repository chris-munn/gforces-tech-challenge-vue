<template>
  <div id="app">
    <img class="logo" src="./assets/logo.svg">
    <h2>{{ data.msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Technical Challenge'
    }
  }
}
</script>

<style>
body {
margin: 0;
font-family: 'Open Sans', sans-serif;
}

#app {
margin-top: 60px;
text-align: center;
color: #303840;
}

.logo { max-width: 500px; }
</style>
