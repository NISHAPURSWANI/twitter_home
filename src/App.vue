<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> | -->
      <!-- <router-link to="/about">About</router-link> -->
      <!-- <router-link to="/homepage">HomePage</router-link> -->
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  // font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;
  margin-top: 0px;
}

#nav {
  // padding: 0px;

  // a {
  //   font-weight: bold;
  //   color: #2c3e50;

  //   &.router-link-exact-active {
  //     color: #42b983;
  //   }
  // }
}
</style>
