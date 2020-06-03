<template>
  <div>
    <app-server-status v-for="sever in 5"></app-server-status>
  </div>
</template>

<script>
import ServiceStatus from "./ServiceState.vue";
export default {
  components: {
    "app-server-status": ServiceStatus
  }
};
</script>

<style></style>
