<template>
  <div id="app">
    <app-banner></app-banner>
    <app-links :links="links"></app-links>
  </div>
</template>

<script>

import banner from './components/Banner.vue';
import links from './components/Links.vue';

export default {
  name: 'app',
  data () {
    return {
      links: [
        {url: '/#about', display: 'About'},
        {url: '/#projects', display: 'Projects'},
      ]
    }
  },
  components: {
    'appBanner': banner,
    'appLinks': links
  }
};
</script>

<style>
body {
  margin: 0px;

  font-family: 'Roboto', sans-serif;
}
</style>
