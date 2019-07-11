<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
body {
  height: 100vh;
}
#app {
  font-family: Helvetica, Arial, sans-serif, sans-serif;
  .button {
    width: 100%;
    text-transform: uppercase;
  }
  max-width: 95%;
  margin: 0 auto;
  padding: 15px 0;
}
</style>
