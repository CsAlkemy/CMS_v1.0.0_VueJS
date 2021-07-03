<template>
  <div class="w-11/12 md:w-9/12 lg:w-8/12 mx-auto py-10">
    <router-view />
  </div>
  <Footer />
</template>

<style lang="scss"></style>
<script>
import Footer from "@/components/layout/Footer";
export default {
  components: { Footer },
};
</script>
