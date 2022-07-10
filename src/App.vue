<template>
<h1>Todo application</h1>
<hr>
<!-- добавление компонента TodoList -->
<TodoList/>
</template>

<script>
// импорт компонента TodoList
import TodoList from '@/components/TodoList'
export default {
  name: 'App',
  components: {
    // регистрация обьекта компонента TodoList
    TodoList: TodoList //можно просто TodoList
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
