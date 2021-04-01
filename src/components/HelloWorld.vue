<template>
  <div class="hello">
    <p class="titlebar">Soumya Technologies</p>
    <div class="main-info">
      <h1>Hello World</h1>
      <h2>We want help you build and develop websites and also maintain them</h2>
    </div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .main-info {
    background: url("../assets/background.jpeg");
    background-size: cover;
    height: 500px;
    padding: 10px;
    padding-top: 20px;
   }
   .titlebar {
     background: black;
     padding: 10px;
     color: white;
     margin: 0px;
   }
</style>
