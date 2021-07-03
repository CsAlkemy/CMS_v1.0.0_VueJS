<template>
  <div class="p-3">
    <VueHero />
  </div>
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
