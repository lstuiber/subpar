<template>

    <b-container >
    <b-row no-gutters>
      <b-col text-left xs="auto" id="nav">
      <b-nav vertical>
      <b-nav-item><router-link to="/">Home</router-link></b-nav-item>
      <b-nav-item><router-link to="/about">About</router-link></b-nav-item>
      <b-nav-item><router-link to="/roster">Roster</router-link></b-nav-item>
      <b-nav-item><router-link to="/schedule">Schedule</router-link></b-nav-item>
      <b-nav-item><router-link to="/alumni">Alumni</router-link></b-nav-item>
      <b-nav-item><router-link to="/photos">Photos</router-link></b-nav-item>
      <b-nav-item><router-link to="/contact">Contact</router-link></b-nav-item>
      </b-nav>
      </b-col>
    <b-col xs="auto">
    test
    </b-col>
    <b-col xs="auto">
      test again
    </b-col>
    </b-row>
    </b-container>

</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
 
  background-image: linear-gradient(to right, darkgreen , green);
  text-align: left;
  width: 25%;
  height: 100vh;
  
  a {
    font-weight: bold;
    color: white;
    text-decoration: none;
    
    

    &.router-link-exact-active {
      color: #42b983;
    }
  }
  li.nav-item {
    list-style-type: none;
    max-width: 20%;
  }
  div.row {
    max-width: 20%;
  }
  ul.nav.flex-column {
    max-width: 20%;
  }
  a:hover {
      color: lightgreen;
    }
}
  b-col {
    width: 30%;
  }
</style>
