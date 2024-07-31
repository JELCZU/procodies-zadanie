<script setup>
import PaymentForm from './PaymentForm.vue'
import PriceTag from './PriceTag.vue'
</script>

<template>
  <div>
    <div>
      <h1>Chance to win a StockX Mystery Box today!</h1>
      <h5>Unleash the Excitement of Mystery Electronics</h5>
    </div>
    <price-tag text1="$1.99" text2="Original value $500"></price-tag>
    <payment-form />
  </div>
</template>

<style scoped></style>
