<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Open+Sans&family=Playfair+Display&display=swap");
/* font-family: 'Montserrat', sans-serif;
font-family: 'Open Sans', sans-serif;
font-family: 'Playfair Display', serif; */
body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: "Playfair Display", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f1e3e3;
}
#nav {
  background-color: #f1e3e3;
  padding: 15px;
}
</style>
