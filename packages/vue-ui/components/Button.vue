<template>
  <button @click="handleClick">Click Me Vue</button>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  methods: {
    handleClick: () => {
      alert("Woooha!");
    },
  },
});
</script>
