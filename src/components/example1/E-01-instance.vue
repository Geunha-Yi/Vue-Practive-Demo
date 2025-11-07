<template>
  <div>Hello, {{ message }}</div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default  defineComponent({
  name: "E01Instance",
  setup() {
    const message = ref('Vue');
    return {
      message
    };
  }
});
</script>

<style scoped>
div {
  color: blue;
}
</style>
