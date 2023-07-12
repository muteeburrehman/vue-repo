<template>
<div>
  <input type="text" ref="inputRef"/>
  <PostList ref="postListRef"/>
</div>
</template>

<script >
import PostList from "@/components/PostList.vue";
export default {
  name:'TemplateRef',
  mounted() {
    console.log(this.$refs.postListRef)
    this.$refs.inputRef.focus()
  },
  components:{
    PostList,
  }
}
</script>

<style scoped>

</style>