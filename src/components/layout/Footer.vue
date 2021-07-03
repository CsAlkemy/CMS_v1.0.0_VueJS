<template>
  <footer
    class="bg-gray-900 fixed bottom-0 w-full rounded-t-2xl sm:rounded-none"
  >
    <div class="flex justify-center mx-auto w-6/12 text-white p-5 sm:p-3">
      <router-link
        to="/"
        exact
        exact-active-class="bg-green-500 rounded-full"
        class="text-white p-3"
        ><HomeIcon class="h-7 w-7"
      /></router-link>
      <router-link
        to="portfolio"
        class="p-3"
        exact
        exact-active-class="bg-green-500 rounded-full"
        ><TerminalIcon class="h-7 w-7"
      /></router-link>
      <router-link
        to="blog"
        class="p-3"
        exact
        exact-active-class="bg-green-500 rounded-full"
        ><RssIcon class="h-7 w-7"
      /></router-link>
      <router-link
        to="/about"
        class="p-3"
        exact
        exact-active-class="bg-green-500 rounded-full"
        ><FireIcon class="h-7 w-7"
      /></router-link>
    </div>
  </footer>
</template>

<script>
import {
  HomeIcon,
  TerminalIcon,
  RssIcon,
  FireIcon,
} from "@heroicons/vue/outline";
export default {
  name: "Footer",
  components: { HomeIcon, RssIcon, TerminalIcon, FireIcon },
  setup() {},
};
</script>

<style scoped></style>
