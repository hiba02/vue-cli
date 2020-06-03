<template>
  <div>
    <p>Server Status: {{ status }}</p>
    <hr />
    <button @click="changeStatus">Change Status</button>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      status: "Critical"
    };
  },
  methods: {
    //ES6 expression
    changeStatus() {
      this.status = "Normal";
    }
  }
};
</script>
