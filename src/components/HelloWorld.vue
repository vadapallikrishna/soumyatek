<template>
  <div class="hello">
    <p>Soumya Technologies</p>
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
    color: white;
  }

  .services {
    background: navy;
    color: white;
    padding-top:20px;
    padding-bottom:20px;
  }

  .services > h3 {
    margin: 0px;
  }

  .inline {
    display: inline-flex;
  }

  .inline > * {
    border: 1px solid lightgrey;
    padding: 10px;
    margin: 10px;
    background: white;
    color: black;
  }
</style>
