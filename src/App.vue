<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">

html {
  height: 100vh;
}

body {
  padding: 0;
  margin: 0;
}

#app {
  font-family: Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  height: 100vh;

}

nav {
  background-color: #F94;
  padding: 1em;
  display: flex;
  gap: 1em;

  a {
    font-weight: bold;
    color: #842;

    &.router-link-exact-active {
      color: #FFF;
    }
  }
}
</style>
