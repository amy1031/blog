<template>
  <div id="app">
  <div class="container">
  <div class="row">
    <div class="col-xs-12">
    <router-view></router-view>
    </div>
  </div>
  </div>
  </div>
</template>

<script>
import New from './components/New'
import Blog from './components/Blog'
import Post from './components/Post'

export default {
  name: 'app',
  components: {
    New,
    Blog,
    Post
  }
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
</style>
