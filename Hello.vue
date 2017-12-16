<template>
  <div>{{greeting}} World!</div>
</template>

<script>
  module.exports = {
    data: function() {
      return {
        greeting: 'Hello'
      }
    },
    mounted: function() {
      console.log('mounted!')
    }
  }
</script>

<style>
  div {
    color: red;
  }
</style>

<style scoped>
  div {
    font-size: 32px;
  }
</style>
