<template>
  <div id="app"> 
    <div class="con">

      <div class="col">
        <h1>Privv CDN</h1>
      </div>

      <div class="col">
        <img src="https://edge.privvcdn.se/banana.gif">
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: 'app',
}
</script>

<style>

body {
  margin: 0px;
  padding: 0px;
  background-size: cover;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
  color: #000;
  display:flex;
  justify-content: center;
  align-items: center;
}

.con{
  max-width: 1200px;
  margin: 0px auto;
  display: flex;
  flex-wrap: wrap;
  width: 100%;
}

.col{
  flex: 0 0 50%;
  text-align: left;
  display: flex;
  align-items: center;
}

h1 {
  font-size: 50px;
}

img {
  width: 400px;
  height: auto;
  display: block;
  max-width: 100%;
  max-height: 100%;
  margin: 0px auto;
}

span {
  font-size: 30px;
}

.column {
  width: 100%;
}
</style>
