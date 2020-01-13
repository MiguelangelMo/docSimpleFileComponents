<template>
  <main id="app" class="ToDo-container">
    <h1 class="ToDo-title">
      Todo List con Vuex
    </h1>
    <todo-add></todo-add>
    <todo-list></todo-list>
    <a href="./">regresar</a>
  </main>
</template>

<script>
import ToDoList from "./components/ToDoList.vue";
import ToDoAdd from "./components/ToDoAdd.vue";

export default {
  components: {
    "todo-list": ToDoList,
    "todo-add": ToDoAdd
  }
};
</script>

<style lang="css">

.completed {
  text-decoration: line-through;
  color: #555;
}
</style>
