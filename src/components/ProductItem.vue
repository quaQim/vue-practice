<template>
  <li>
    <p class="title">아오</p>
    <p class="image">
      <img
        :src="`https://placeimg.com/100/100/${product.id}`"
        alt="product.name"
      />
    </p>
    <p class="price">{{ product.price }}</p>
  </li>
</template>

<script>
export default {
  name: "product-item",
  props: {
    product: Object,
  },
};
</script>

<style scoped>
li {
  border: 4px solid aquamarine;
  margin-bottom: 1em;
}
.title {
  font-size: 30px;
  color: yellowgreen;
  font-weight: bold;
}
</style>
