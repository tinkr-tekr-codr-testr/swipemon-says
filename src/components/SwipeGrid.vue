<template>
  <div v-for="i in x" :key="i">
    <div v-for="j in y" :key="i + '' + j">{{ x }}, {{ y }}</div>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  x: Number,
  y: Number,
});
</script>
