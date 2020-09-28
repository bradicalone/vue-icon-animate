<template>
  <div id="app">
    <react></react>
  </div>
</template>


<script>
import React from './React'

export default {
  name: 'app',
  components: {
    'react': React
  },
  data () {
    return {
      msg: ''
    }
  },
  methods: {

  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
