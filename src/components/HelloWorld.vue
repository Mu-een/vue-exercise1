<template>
  <div class="hello">
    <h2>The Game Cave</h2>
    <img src="https://i.postimg.cc/j2R56GQ7/e0687cb0fc639ccf55adc2cdfddd2027.jpg" alt="">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
img {
  border-radius: 300px;
}
</style>
