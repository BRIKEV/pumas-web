<template>
  <section class="ui container">
    <div class="doubts">
      <div class="img-container">
        <video loop muted autoplay src="/images/pumas/players-celebration.mp4" alt="basketball blackboard"></video>
      </div>
      <div class="doubt-list">
        <h2>Dudas frequentes</h2>
        <details class="ui card fluid">
          <summary class="content bold">¿Donde jugamos?</summary>
          <div class="content">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus a porro culpa exercitationem veritatis quae perferendis, cumque architecto voluptate repellendus temporibus non quibusdam maxime ex sed tempora vero eaque.
          </div>
        </details>
        <details class="ui card fluid">
          <summary class="content bold">Donde se comunican novedades</summary>
          <div class="content">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus a porro culpa exercitationem veritatis quae perferendis, cumque architecto voluptate repellendus temporibus non quibusdam maxime ex sed tempora vero eaque.
          </div>
        </details>
        <details class="ui card fluid">
          <summary class="content bold">duda 1</summary>
          <div class="content">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus a porro culpa exercitationem veritatis quae perferendis, cumque architecto voluptate repellendus temporibus non quibusdam maxime ex sed tempora vero eaque.
          </div>
        </details>
        <details class="ui card fluid">
          <summary class="content bold">duda 1</summary>
          <div class="content">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsam doloribus a porro culpa exercitationem veritatis quae perferendis, cumque architecto voluptate repellendus temporibus non quibusdam maxime ex sed tempora vero eaque.
          </div>
        </details>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.doubts {
  display: flex;
  gap: 20px;
  margin-bottom: 5em;
  .img-container {
    display: none;
  }
  .doubt-list {
    width: 100%;
  }
  @include desktop {
    .img-container {
      display: block;
      img {
        width: 100%;
      }
    }
  }
}
</style>
