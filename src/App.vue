<script setup lang="ts">
import { ref } from "vue";
const test = ref(0);
</script>

<template>
  <div>
    <pre>
      {{ test }}
    </pre>
  </div>
</template>
