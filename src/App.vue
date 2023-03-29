<script setup>
import { ref, computed } from 'vue';

const numbers = ref([0, 1, 2, 3]);
const lastNumber = computed(() => numbers.value.at(-1));
</script>

<template>
  {{ lastNumber }}
</template>

