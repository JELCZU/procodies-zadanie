<script setup>
import PaymentForm from './PaymentForm.vue'
import ImageThumbnailsComponent from './ImageThumbnailsComponent.vue'
import PriceTag from './PriceTag.vue'
</script>

<template>
  <div clas="d-flex">
    <section>
      <image-thumbnails-component></image-thumbnails-component>
      <price-tag text1="$1.99" text2="Original value $500"></price-tag>
    </section>
    <section>
      <div class="margin-bottom-23px">
        <h1 class="m-0">Chance to win a StockX Mystery Box today!</h1>
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
