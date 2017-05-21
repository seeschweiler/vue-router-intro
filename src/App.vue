<template>
  <div class="container" id="app">
    <div class="alert alert-warning alert-dismissible" role="alert">
      <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
      <strong><a href="http://codingthesmartway.com/courses/vue-beginner-professional/" target="_blank">[ONLINE COURSE] - Vue.js 2 - From Beginner To Professional</a></strong> +++ Understand the theory of Vue.js and how it works under the hood. +++  How to manage state in large Vue applications with Vuex +++ Use modern tools for developing and building Vue applications (e.g. webpack) +++
    </div>
    <img src="./assets/logo.png">
    <div class="">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/firstroute/Peter">FirstRoute</router-link></li>
        <li><router-link to="/firstroute/Peter/child">FirstRouteChild</router-link></li>
      </ul>

    </div>
    <router-view></router-view>
    <br/><br/><hr/>
    <div class="footer">
      <p>&copy <a href="http://codingthesmartway.com" target="_blank">CodingTheSmartWay.com</a> | <a href="http://codingthesmartway.com/imprint" target="_blank">Imprint</a></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
