<script setup lang="ts">
  const props = defineProps<{
    label: string
  }>()
</script>

<template>
  <button>{{ props.label }}</button>
</template>

<style scoped></style>
