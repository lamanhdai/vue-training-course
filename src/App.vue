<script setup>
import {ref, onCreated} from 'vue'

  let message = ref('');



  const greetMessage = () => {
    message.value = 'Hello Vue Composition API';
  }


  onCreated(()=> {
    greetMessage();
  })
</script>

<template>
    <div class="text-center">{{ message }}</div>
</template>

<style scoped>
.text-center {
    text-align: center;
}
</style>
