<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <Filters />
      <Todos />
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos'
import AddTodo from './components/AddTodo'
import Filters from './components/Filters'

export default {
  name: 'App',
  components: {
    Todos,
    AddTodo,
    Filters
  }
}
</script>

<style>
body {
  background: #e8f7f0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: hidden;
  padding: 0 2rem;
}
</style>
