<script setup>
import InfoArticle from './InfoArticle.vue'

const articles = [
  {
    title: 'How can I win?',
    text: 'Thanks to your membership, you also participate in our contest to win the iPhone15. We sellect a winner among every 600 participants. The next winner will be selected on 06.10.2023, and will be notified directly by e-mail. If the reward is out of stock, the winner will receive a similar product of equal or greater value instead.',
    id: 1
  },
  {
    title: 'No hidden fees?',
    text: 'We ensure that our members are provided with a detailed history of transactions so that they know exactly what they are paying for. Credit card information is only required to facilitate future purchases. There will be no charges on your credit card statement if you do not upgrade to PREMIUM membership and do not make a purchase.',
    id: 2
  },
  {
    title: 'Why do we need your billing information?',
    text: "By joining this service, you will receive a 5-day trial of our partner's program. If you continue with a subscription beyond the 5-day trial period, you will be charged an amount on your credit card which varies depending on the choice of the tariff. When your contribution is deducted from your credit card or other payment method, you will have access to these services which are reserved exclusively for members of our partner's website.",
    id: 3
  }
]
</script>

<template>
  <div class="bg-white-smoke">
    <div class="d-flex flex-row m-0 pb-6 pt-6">
      <info-article
        class="ml-4 mr-4"
        v-for="article in articles"
        v-bind:key="article.id"
        :title="article.title"
        :text="article.text"
      />
    </div>
  </div>
</template>

<style scoped></style>
