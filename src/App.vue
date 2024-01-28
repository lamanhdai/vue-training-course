<script setup>
import {ref, onCreated} from 'vue'
  let message = ref('');
  onCreated(()=> {
    message.value = 'Hello Vue Composition API';
  })
</script>

<template>
    <div>{{ message }}</div>
</template>

<style scoped>
</style>
