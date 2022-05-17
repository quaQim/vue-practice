<template>
  <h2 v-bind="$attrs">Hello {{ username }}!</h2>
  <h3>내가 {{ numberOfVisit }}이나 보고싶었구나!</h3>
</template>
<script>
export default {
  name: "GreetingUser",
  props: {
    username: String,
    numberOfVisit: {
      type: Number,
      default: 0,
    },
  },
};
</script>
<style scoped></style>
