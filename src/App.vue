<template>
  <div id="app">
    <h1 class="title">Hi, I'm Negin</h1>
    <img class="icon" src="./assets/logo.png" />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Inconsolata&display=swap");
#app {
  font-family: "Inconsolata", monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: auto;
  grid-template-areas:
    "title . . ."
    "icon . . . "
    "blog blog blog blog"; */
}

body {
  display: flex;
  flex-direction: column;
}

/* .icon,
.title {
  border-radius: 50%;
  grid-area: icon;
  display: flex;
} */

img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
}
</style>
