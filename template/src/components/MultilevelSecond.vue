<template>
  <div class="multilevelsecondlink">
    <h1>{{ msg }}</h1>
  	<h2>With an awesome title</h2>
    <p>But nothing behind...</p>
  </div>
</template>

<script>
export default {
  name: 'multilevelsecondlink',
  data () {
    return {
      msg: 'This is a second page for Multilevel'
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
