<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>thx <a href="//balmjs.com/">BalmJS</a> & <a href="//balmjs.com/ui-vue/">BalmUI</a></p>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Hello Vue App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
