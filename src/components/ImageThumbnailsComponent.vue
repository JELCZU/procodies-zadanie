<script setup>
import { ref } from 'vue'
import PriceTag from './PriceTag.vue'
const images = ref([
  {
    src: '/src/assets/stock/Stock2.png',
    alt: 'Stock image 2',
    id: 2
  },
  {
    src: '/src/assets/stock/Stock3.png',
    alt: 'Stock image 3',
    id: 3
  },
  {
    src: '/src/assets/stock/Stock4.png',
    alt: 'Stock image 4',
    id: 4
  }
])
let selectedImage = ref({
  src: '/src/assets/stock/Stock1.png',
  alt: 'Stock image 1',
  id: 1
})

function changeMainImage(id) {
  const index = images.value.findIndex((el) => el.id === id)
  if (index > -1) {
    const temp = images.value.splice(index, 1, selectedImage.value)[0]
    selectedImage.value = temp
  }
}
</script>

<template>
  <div>
    <price-tag class="price-tag" text1="$1.99" text2="Original value $500" />
    <div class="image-thumbnail-component">
      <img class="selected-image mb-4" :src="selectedImage.src" :alt="selectedImage.alt" />
      <section class="d-flex justify-content-space-between">
        <img
          v-for="img in images"
          :key="img.id"
          class="image-thumbnail"
          :src="`${img.src}`"
          :alt="img.alt"
          @click="changeMainImage(img.id)"
        />
      </section>
    </div>
  </div>
</template>

<style scoped>
.image-thumbnail-component {
  display: flex;
  width: 30rem;
  flex-direction: column;
}
.image-thumbnail {
  cursor: pointer;
  border-radius: 13.94px;
  height: 8.25rem;
  width: 8.25rem;
  border-color: var(--primary-color);
  border-width: 0.93px;
  border-style: solid;
}
.selected-image {
  height: 30rem;
  width: auto;
}
.price-tag {
  position: relative;
  margin-left: calc(20rem + 5px);
  margin-bottom: -9rem;
  height: 10rem;
}
/* .image-thumbnail:; */
</style>
