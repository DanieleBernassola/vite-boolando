<script>
export default {
  name: 'CardElement',
  props: [
    'img1', 'img2', 'brand', 'name', 'price'
  ]
}
</script>

<template>
  <div class="col-33">
    <div class="content">
      <img class="main-image" :src="img1" :alt="name">
      <img class="hover-image" :src="img2" :alt="name">
      <div class="heart">&hearts;</div>
      <div class="label">
        <span class="discount-label">-50%</span>
        <span class="eco-label">Sostenibilit&agrave;</span>
      </div>
      <!-- INFORMAZIONI PRODOTTO -->
      <div>
        <div class="brand">{{ brand }}</div>
        <div class="prod-name">{{ name }}</div>
        <div class="new-price"> &euro;</div>
        <div class="old-price">{{ price }} &euro;</div>
      </div>
    </div>
  </div>
</template>

<style lang="scss"></style>