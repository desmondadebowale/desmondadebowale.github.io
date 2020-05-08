<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/blog">Blog</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/portfolio">Portfolio</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
body{
  background-color: rgb(190, 218, 113);
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 16px;
  line-height: 1.4em;
  margin: 0;
  text-align: center;
}

#nav {
  padding: 10px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  padding-right: 20px;
}

#nav a.router-link-exact-active {
  color: #42b983;
  
}
</style>
