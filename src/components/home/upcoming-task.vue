<template>
  <div class="upcoming-task">
    <div class="upcoming-task-header">
      <h1>Today</h1>
      <div>See All</div>
    </div>
    <task-list></task-list>
  </div>
</template>
<script>
import TaskList from "@/components/home/task-list.vue";

export default {
  components: {
    TaskList,
  },
};
</script>