<template>
  <div class="top-bar">
    <div class="left-top-bar">
      <div class="left-top-bar-time">12:22</div>
      <div class="left-top-bar-iocn">
        <location-icon></location-icon>
      </div>
    </div>
    <div class="right-top-bar">
      <div class="right-top-bar-iocn">
        <bar-icon></bar-icon>
        <network-icon></network-icon>
        <battery-icon></battery-icon>
      </div>
    </div>
  </div>
</template>
<script>
import LocationIcon from "@/components/icons/location-icon.vue";
import BarIcon from "@/components/icons/bar-icon.vue";
import NetworkIcon from "@/components/icons/network-icon.vue";
import BatteryIcon from "@/components/icons/battery-icon.vue";

export default {
  name: "header",
  components: {
    LocationIcon,
    BarIcon,
    NetworkIcon,
    BatteryIcon,
  },
};
</script>