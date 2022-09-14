<template>
  <h3>AppComponent username {{ name }}</h3>
  <ComponentC />
</template>

<script>
import ComponentC from "@/components/ComponentC.vue";
export default {
  name: "App",
  components: {
    ComponentC,
  },
  data() {
    return {
      name: "Vishwas",
    };
  },
  provide() {
    return {
      username: this.name,
    };
  },
};
</script>

<style>
</style>