<template>
  <ul>
    <li v-for="link in links">
      <a :href="link.url">{{ link.display }}</a>
    </li>
  </ul>
</template>

<script>
  export default {
    props: {
      links: {
        type: Array
      }
    }
  };

</script>

<style scoped>
  ul {
    list-style: none;
    display: block;
    text-align: center;
  }

  li {
    display: inline-block;
    padding: 10px;
  }

  li:hover {
    background: #ccc;
  }

  a {
    color: black;
    text-decoration: none;
    font-size: 20px;
  }
</style>
