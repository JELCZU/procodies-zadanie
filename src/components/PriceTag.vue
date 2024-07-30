<script setup>
defineProps({
  text1: { default: '' },
  text2: { default: '' }
})
</script>

<template>
  <div>
    <div>
      <h1>{{ text1 }}</h1>
      <h3>{{ text2 }}</h3>
    </div>
  </div>
</template>

<style scoped></style>
