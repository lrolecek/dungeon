<template>
  <div id="app">

    <h1>Tajemný hrad</h1>

    <dungeon />

  </div>
</template>

<script>
import Dungeon from './components/Dungeon.vue'

export default {
  name: 'App',
  components: {
    dungeon: Dungeon
  }
}
</script>

<style>
#app {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1 {
  text-align: center;
}
</style>
