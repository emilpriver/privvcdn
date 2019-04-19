<template>
  <div id="app">
    <div class="wrapper">
        <div class="column">
          <a href="https://emilpriver.com">
            <img src="https://edge.privvcdn.se/portfolio/vitlogotyp.png" />
          </a>
        </div>
        <span>Global CDN network hosted by DigitalOcean</span>
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
  background-image: url('https://edge.privvcdn.se/cdn_bg.jpg');
  background-size: cover;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
  color: #fff;
  display:flex;
  justify-content: center;
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
