<template>
  <div class="grid grid-cols-1 md:grid-cols-2 gap-3 my-10">
    <div class="col-span-1  bg-gray-900 rounded-lg">
      <div>
        <UserForm />
      </div>
    </div>
    <div class="col-span-1 bg-gray-900 rounded-lg">
      <div>
        <LiveEditor />
      </div>
    </div>
    <div class="col-span-2 bg-black rounded-lg">
      <div>
        <BlogList />
      </div>
    </div>
  </div>
</template>

<script>
import UserForm from "@/components/User/userForm";
import LiveEditor from "@/components/User/liveEditor";
import BlogList from "@/components/User/blogList";
export default {
  name: "User",
  components: {BlogList, LiveEditor, UserForm}
}
</script>

<style scoped>

</style>