<template>
  <div>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4 m-0 md:m-10 text-white">
      <div class="col-span-1 md:row-span-2 bg-gray-900 rounded-2xl">
        <SideNav />
      </div>
      <div class="col-span-1 bg-gray-900 rounded-2xl">
        <h1 class="text-center text-2xl font-bold my-10">Portfolio</h1>
      </div>
      <div class="col-span-1 bg-gray-900 rounded-2xl">
        <h1 class="text-center text-2xl font-bold my-10">Blog</h1>
      </div>
      <div class="col-span-1 md:col-span-2 bg-gray-900 rounded-2xl">
        <h1 class="text-center text-2xl font-bold my-10">About</h1>
      </div>
    </div>
  </div>
</template>

<script>
import SideNav from "@/components/Home/sideNav.vue";
export default {
  name: "Home",
  components: { SideNav },
};
</script>

<style scoped></style>
