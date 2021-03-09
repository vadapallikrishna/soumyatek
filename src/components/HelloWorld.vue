<template>
  <div class="hello">
    <div class="main-info">
      <h1>Hello World from Soumya Technologies</h1>
      <h1>WhatsApp at +918374265403</h1>
    </div>
    <div class="services">
      <h3>Basic Services</h3>
      <div class="inline">
        <h2>Wordpress</h2>
        <h2>Graphic Design</h2>
        <h2>Web Design</h2>
        <h2>Cpanel</h2>
        <h2>React</h2>
        <h2>Vue</h2>
      </div>
    </div>
    <div class="services">
      <h3>Cloud Services</h3>
      <div class="inline">
        <h2>Software Installation</h2>
        <h2>Saas</h2>
        <h2>Database Administration</h2>
        <h2>Api Testing</h2>
      </div>
    </div>
    <div class="services">
      <h3>Mobile App Development</h3>
      <div class="inline">
        <h2>Android</h2>
        <h2>React Native</h2>
        <h2>Flutter</h2>
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
    background: lightblue;
    height: 300px;
    padding: 10px;
  }

  .services {
    background: navy;
    color: white;
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
