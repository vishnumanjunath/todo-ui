<template>
  <div class="actions">
    <time-icon></time-icon>
    <add-icon></add-icon>
    <pie-chart-icon></pie-chart-icon>
  </div>
</template>
<script>
import TimeIcon from "@/components/icons/time-icon.vue";
import AddIcon from "@/components/icons/add-icon.vue";
import PieChartIcon from "@/components/icons/pie-chart-icon.vue";

export default {
  components: {
    TimeIcon,
    AddIcon,
    PieChartIcon,
  },
};
</script>