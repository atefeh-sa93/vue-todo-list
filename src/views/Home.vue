<template>
  <div class="home">
    <TodoList />
  </div>
</template>

<script>
import TodoList from "@/components/TodoList";
export default {
  name: "Home",
  components: {
    TodoList
  }
};
</script>
