<template>
  <div class="container">
    post item
    <p>
      {{postId}}
    </p>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  head() {
    return {
      title: "Post Page",
      meta: [{name:'twiter',content:'fewregregreg'}]
    };
  },
  data() {
    return {
      postId: this.$route.params.id
    };
  }
};
</script>

<style>
</style>
