<template>
  <NuxtLink :to="path">
    <div class="news-item">
      <div class="image-container">
        <img :src="image" alt="new 1">
      </div>
      <div class="news-text">
        <h4>{{ title }}</h4>
        <h6>{{ date }}</h6>
      </div>
    </div>
  </NuxtLink>
</template>
<script setup lang="ts">
type Props = {
  title: string;
  path: string;
  image: string;
  date: string;
};
defineProps<Props>()
</script>
<style lang="scss" scoped>
.news-item {
  display: flex;
  gap: 20px;
  justify-content: space-between;
  .image-container {
    max-width: 80px;
    img {
      width: 100%;
    }
  }
  .news-text {
    color: $white;
  }
}
</style>
