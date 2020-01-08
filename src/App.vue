<template>
  <div id="app">
    
  <div class="container">
    <div class="columns">
      <div class="column col-11">
        <router-view/>
      </div>
      <div class="column col-1">
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/portfolio">Portfolio</router-link></li>
          <li><router-link to="/films">Films</router-link></li>
          <li><router-link to="/music">Music</router-link></li>
          <li><router-link to="/about">About</router-link></li>
          <li><router-link to="/archive">Archive</router-link></li>
        </ul>
      </div>
    </div>
  </div>
    
</div>
</template>



<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

ul {
  list-style-type: none;
  margin: 0;
}

/*#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}*/
</style>
