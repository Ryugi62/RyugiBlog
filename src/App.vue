<template>
  <div id="nav">
    <router-link to="/">
      <img class="homeImg" src="@/assets/logo.png" />
    </router-link>
    <router-link to="/spring">Spring</router-link> |
    <router-link to="/summer">Summer</router-link> |
    <router-link to="/fall">Fall</router-link> |
    <router-link to="/winter">Winter</router-link>
  </div>
  <router-view />
</template>

<style lang="scss">
#app {
  color: #2c3e50;
  text-align: center;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

#nav {
  padding: 30px;

  a {
    color: #2c3e50;
    font-weight: bold;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

.homeImg {
  top: 0;
  left: 0;
  width: 35px;
  margin: 10px;
  position: absolute;
}
</style>
