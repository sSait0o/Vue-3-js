<template>
  <main>
    <h1></h1>
    <p>{{ count }}</p>
    <button @click="increment">Incrémenter</button>
  </main>
</template>
<script setup lang="ts">
import { ref } from "vue";
const count = ref(0);

const increment = () => {
  count.value++;
};
</script>
