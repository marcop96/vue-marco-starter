<script setup lang='ts'>
import { ref } from 'vue';

const intro = ref('Marco starter template!')
</script>

<template>
  <div class="flex flex-col items-center justify-center min-h-screen bg-red-500">
    <h1 class="text-4xl font-bold text-white">
      {{ intro }}
    </h1>
  </div>
</template>
