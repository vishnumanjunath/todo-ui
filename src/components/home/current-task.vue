<template>
  <div class="current-task">
    <div class="current-task-header">
      <h1>00:32:10</h1>
      <right-arrow-icon></right-arrow-icon>
    </div>
    <div class="current-task-description">
      <current-task-progress-icon></current-task-progress-icon>
      <div class="task-description">Rasion Project</div>
    </div>
  </div>
</template>
<script>
import RightArrowIcon from "@/components/icons/right-arrow-icon.vue";
import CurrentTaskProgressIcon from "@/components/icons/current-task-progress-icon.vue";
export default {
  components: {
    RightArrowIcon,
    CurrentTaskProgressIcon,
  },
};
</script>