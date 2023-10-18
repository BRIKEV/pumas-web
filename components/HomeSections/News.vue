<template>
  <section class="news">
    <NewsItem
      v-for="newItem in news"
      :title="newItem.title"
      :date="newItem.date"
      image="/images/pumas/trophies.jfif"
      :path="newItem._path"
    />
  </section>
</template>
<script setup lang="ts">
const { data: news } = await useAsyncData('news', () => 
  queryContent('/novedades')
  .only(['date', 'title', '_path'])
  .limit(4)
  .sort({ date: -1 })
  .find()
);
</script>
<style lang="scss" scoped>
.news {
  background-color: $black;
  padding: 2em;
  margin-bottom: 5em;
  @include desktop {
    display: flex;
    justify-content: space-around;
    gap: 10PX;
  }
}
</style>
