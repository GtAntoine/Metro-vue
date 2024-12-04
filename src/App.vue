<template>
  <MetroMap></MetroMap>
</template>

<script>
import MetroMap from './components/MetroMap.vue'

export default {
  name: 'App',
  components: {
    MetroMap
  }
}
</script>

<style>
#app {
  color: #2c3e50;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 60px;
}

body {
  background-color: #fffbdc;
}

</style>
