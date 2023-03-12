<script setup>
import Time from './components/TimerOne.vue'
</script>

<template>
  <Time :show-saved-times="true" />
</template>

<style>
@import './assets/base.css';

#app {
  margin: 100px auto;
}

.green {
  color: hsla(160, 100%, 37%, 1);
}
</style>
