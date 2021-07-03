<template>
  <div class="text-white p-3">
    <h1 class="text-2xl font-semibold tracking-tight text-gray-300">
      Hello.
    </h1>
    <h2 class="text-lg tracking-tight font-light">
      My Name Is <span class="text-blue-500 font-bold">Alkemy</span>
    </h2>
    <p class="text-sm pb-7 font-light tracking-tighter ">
      I'm a Software Developer
    </p>
    <ul class="flex flex-row mx-auto justify-start gap-x-4">
      <a href="tel:01521109475"><PhoneIcon class="h-5 w-5 text-white"/></a>
      <a href="mailto:alkemy48@gmail.com"
        ><MailIcon class="h-5 w-5 text-white"
      /></a>
      <a href="https://github.com/CsAlkemy" target="_blank"
        ><TerminalIcon class="h-5 w-5 text-white"
      /></a>
      <router-link to="user">
        <LoginIcon class="h-5 w-5 text-gray-900"  />
      </router-link>
    </ul>
  </div>
</template>
<script>
import { PhoneIcon, MailIcon, TerminalIcon, LoginIcon } from "@heroicons/vue/outline";

export default {
  name: "vueHero",
  components: { PhoneIcon, MailIcon, TerminalIcon, LoginIcon },
};
</script>

<style scoped></style>
