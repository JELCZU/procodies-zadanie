<script setup>
defineProps({
  title: { default: '' },
  text: { default: '' }
})
</script>

<template>
  <div>
    <h1>{{ title }}</h1>
    <h2>{{ text }}</h2>
  </div>
</template>

<style scoped></style>
