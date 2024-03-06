<script setup>
import AddTodo from "./components/AddTodo.vue";
import Todos from "./components/Todos.vue";
import FilterTodos from "./components/FilterTodos.vue";
</script>

<template>
  <header>
    <div class="container">
      <AddTodo />
      <FilterTodos />
      <Todos />
    </div>
  </header>
</template>

<style scoped>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
