<template>
  <q-page class="row items-center justify-evenly">
    <swipe-grid :x="3" :y="3" />
  </q-page>
</template>

<script setup lang="ts">
import SwipeGrid from 'src/components/SwipeGrid.vue';
defineOptions({
  name: 'IndexPage',
});
</script>
