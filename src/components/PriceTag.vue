<script setup>
defineProps({
  text1: { default: '' },
  text2: { default: '' }
})
</script>

<template>
  <div>
    <div class="bg-primary circle">
      <div class="d-flex flex-column justify-content-center align-items-center">
        <h4 class="white m-0 mb-2">{{ text1 }}</h4>
        <label class="white text2">{{ text2 }}</label>
      </div>
    </div>
  </div>
</template>

<style scoped>
.circle {
  aspect-ratio: 1;
  height: 100%;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.text2 {
  font-size: 0.875rem;
}
</style>
