<template>
  <h2>{{text}}</h2>
</template>

<script>
export default {
  name: 'Header',
  data(){
    return{
      text: 'A Simple Reactive Calculator created with Vue.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 40px 0 20px 0;
}

a {
  color: #42b983;
}
</style>
