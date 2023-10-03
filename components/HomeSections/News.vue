<template>
  <section class="news">
    <div class="news-item">
      <div class="image-container">
        <img src="/images/team_court_compressed.avif" alt="new 1">
      </div>
      <div class="news-text">
        <h4>Bulls hold off Pacers to improve to 3-2, LaVine scores 28</h4>
        <h6>October 30, 2022</h6>
      </div>
    </div>
    <div class="news-item">
      <div class="image-container">
        <img src="/images/team_court_compressed.avif" alt="new 1">
      </div>
      <div class="news-text">
        <h4>Bulls hold off Pacers to improve to 3-2, LaVine scores 28</h4>
        <h6>October 30, 2022</h6>
      </div>
    </div>
    <div class="news-item">
      <div class="image-container">
        <img src="/images/team_court_compressed.avif" alt="new 1">
      </div>
      <div class="news-text">
        <h4>Bulls hold off Pacers to improve to 3-2, LaVine scores 28</h4>
        <h6>October 30, 2022</h6>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.news {
  background-color: $black;
  padding: 30px;
  margin-bottom: 40px;
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
}
</style>
