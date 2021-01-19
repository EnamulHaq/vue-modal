<template>
  <h1 v-if="title" >Hello i am here</h1>
  <p v-else >Hey this is paragraph</p>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      title: true
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
