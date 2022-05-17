<template>
  <div>
    <h2>Hello component!</h2>
    <CompLevel1 />
  </div>
</template>

<script>
import CompLevel1 from "./components/provide-inject/CompLevel1.vue";
export default {
  name: "App",
  components: { CompLevel1 },
  data() {
    return {
      username: "cherry",
    };
  },
  computed: {},
  watch: {},
  directives: {},
  methods: {},
};
</script>

<style></style>
