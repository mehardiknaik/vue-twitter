<template>
  <div>
    <div v-for="item in posts" :key="item.name">

      <PostItem v-bind="item" />
    </div>
  </div>
</template>
  
<script>
import PostItem from './PostItem.vue';
import posts from "../Data/post"
export default {
  name: 'CenterContainer',
  components: {
    PostItem,
  },
  data() {
    return {
      posts
    }
  }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
  