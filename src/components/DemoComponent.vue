<script setup>
import { ref } from 'vue';
import { NButton } from 'naive-ui';

const count = ref(0);
</script>
<template>
  <NButton type="primary" @click="() => count++"> count++: {{ count }} </NButton>
</template>
