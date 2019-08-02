<template>
  <div class="home">
    <div class="todo-wrapper">
      <TodoList />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld.vue';
import TodoList from '../components/TodoList.vue';

export default {
  name: "home",
  components: {
    TodoList,
    HelloWorld,
  }
};
</script>
