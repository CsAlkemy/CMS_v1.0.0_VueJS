<template>
  <div class="p-5 m-4 w-4/5 mx-auto">
    <h1 class="text-2xl text-white font-semibold">Add New Blog</h1>
    <div class="flex flex-col">
      <input placeholder="Title" class="form-Custom">
      <input placeholder="Subtitle" class=" form-Custom">
      <textarea placeholder="Write here.." class="form-Custom" rows="5" cols="1"></textarea>
      <button class="btn-indigo" >Submit</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "UserForm"
}
</script>

<style>
.btn-indigo {
  @apply py-2 px-4 bg-green-500 text-white font-semibold rounded-sm shadow-md hover:bg-green-600 focus:outline-none focus:ring-2 focus:ring-indigo-400 focus:ring-opacity-75;
}
.form-Custom{
  @apply bg-gray-50 pl-3 my-2 rounded-sm p-2 shadow-sm
}
</style>