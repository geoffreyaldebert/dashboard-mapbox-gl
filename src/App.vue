<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<style>
body {
  margin: 0;
}
#app {
  display: flex;
  position: absolute;
  width: 100%;
  height: 100%;
}
</style>
