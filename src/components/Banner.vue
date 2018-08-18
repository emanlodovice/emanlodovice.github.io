<template>
  <div class="container">
    <img src="../assets/talk2.jpg" alt="">
    <h1>Emmanuel Lodovice</h1>    
  </div>
</template>

<script>
    export default {
      name: 'Banner'
    };
</script>

<style scoped>
  .container {
    display: block;
    background-color: #FFFFFF;
    padding-top: 20px;
  }
  
  img {
    display: block;
    width: 200px;
    height: 200px;
    margin: 0 auto;
    border-radius: 100px;
    object-fit: cover;
    border: 3px solid #ccc;
  }

  h1 {
    margin-top: 10px;
    margin-bottom: 10px;
    font-size: 4em;
    text-align: center;
  }

  @media only screen and (max-width: 600px) {
    h1 {
      font-size: 2em;
    }
  }
</style>