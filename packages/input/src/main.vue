<template>
  <input type="text" :value="value">
</template>

<script>
import { ref } from 'vue';

export default {
  name: 'KInput',
  setup() {
    const value = ref('');
    return { value };
  },
};
</script>

<style>
</style>
