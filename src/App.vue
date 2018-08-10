<template>
  <div id="app">
    <app-nav></app-nav>
  </div>
</template>

<script>

import nav from './components/nav.vue';

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    'appNav': nav
  }
};
</script>

<style>
body {
  background-image: url('./assets/talk.jpg');
  background-size: cover;
  margin: 0px;

  font-family: 'Roboto', sans-serif;
}
</style>
