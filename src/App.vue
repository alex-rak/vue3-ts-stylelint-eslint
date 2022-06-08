<template>
  <nav>
    <RouterLink to="/">
      Home
    </RouterLink> |
    <RouterLink to="/about">
      About
    </RouterLink>
  </nav>
  <RouterView />
</template>

<style lang="scss">
#app {
  position: relative;
  display: flex;
  color: #2c3e50;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

nav {
  padding: 30px;

  a {
    color: #2c3e50;
    font-weight: bold;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
