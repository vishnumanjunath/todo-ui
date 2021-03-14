<template>
  <div id="container">
    <top-header></top-header>
    <div class="header">
      <div class="heading">Task</div>
      <more-icon></more-icon>
    </div>
    <current-task></current-task>
    <upcoming-task></upcoming-task>
    <actions></actions>
  </div>
</template>

<script>
import MoreIcon from "@/components/icons/more-icon.vue";
import CurrentTask from "@/components/home/current-task.vue";
import UpcomingTask from "@/components/home/upcoming-task.vue";
import TopHeader from "@/components/home/top-header.vue";
import Actions from "@/components/home/actions.vue";

export default {
  name: "Home",
  components: {
    MoreIcon,
    CurrentTask,
    UpcomingTask,
    TopHeader,
    Actions,
  },
};
</script>
