<template>
  <div class="home-my-feed"><ArticleList type="feed" data-qa="article-preview"/></div>
</template>

<script>
import ArticleList from "@/components/ArticleList.vue";
export default {
  name: "home-my-feed",
  components: {
    ArticleList
  }
};
</script>
