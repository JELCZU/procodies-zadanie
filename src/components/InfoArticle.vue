<script setup>
defineProps({
  title: { default: '' },
  text: { default: '' }
})
</script>

<template>
  <div>
    <p class="font-weight-600 p-0 m-0 mb-1">{{ title }}</p>
    <p class="x-small m-0 p-0">{{ text }}</p>
  </div>
</template>

<style scoped></style>
