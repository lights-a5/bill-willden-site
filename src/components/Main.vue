<template>
  <div class="hello">
    <img src="../assets/logo.png" alt="Logo">
    <div id="card1">div1</div>
    <div id="buttonDiv">
      <button>Github</button>
      <button>LinkedIn</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
