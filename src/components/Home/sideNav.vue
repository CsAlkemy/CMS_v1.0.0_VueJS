<template>
  <router-link to="/" class="p-3">
    <VueHero />
  </router-link>
</template>

<script>
import VueHero from "@/components/About/vueHero";
export default {
  name: "sideNav",
  components: { VueHero },
  setup() {
    return {};
  },
};
</script>

<style scoped></style>
