<template>
  <div class="hello">
    <h1>Choudry Abdul Rehman</h1>
    <h2>Software Engineering, Knox College</h2>
    <div>{{ msg }}</div>
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
.hello div{
  margin: 0 20%;
}
</style>
