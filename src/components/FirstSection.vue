<script setup>
import PaymentForm from './PaymentForm.vue'
import ImageThumbnailsComponent from './ImageThumbnailsComponent.vue'
</script>

<template>
  <div class="d-flex justify-content-center align-items-center">
    <section>
      <image-thumbnails-component></image-thumbnails-component>
    </section>
    <section class="mr-4 ml-4">
      <div class="margin-bottom-23px">
        <h1 class="m-0 mb-2">Chance to win a StockX Mystery Box today!</h1>
        <span class="subtitle">Unleash the Excitement of Mystery Electronics</span>
      </div>
      <payment-form />
    </section>
  </div>
</template>

<style scoped>
.subtitle {
  font-size: 1.375rem;
  font-weight: 400;
}
.margin-bottom-23px {
  margin-bottom: 23px;
}
</style>
