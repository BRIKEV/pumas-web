<template>
  <section class="ui container bio">
    <div>
      <h2>Stay connected. Stay active. Play hard.
      </h2>
      <p>Penatibus dapibus ac condimentum curae egestas auctor elit scelerisque felis mi blandit. Massa nibh posuere
        scelerisque curae ornare lacinia sapien.</p>
      <div>
        <div class="bio-item">
          <div>
            <i class="basketball ball icon"></i>
          </div>
          <div>
            <div>
              <h4>
                Basketball Club &amp; Community </h4>
            </div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis,
              pulvinar dapibus leo. </p>
          </div>
        </div>
        <div class="bio-item">
          <div>
            <i class="users icon"></i>
          </div>
          <div>
            <div>
              <h4>
                Course &amp; Professional Training </h4>
            </div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut elit tellus, luctus nec ullamcorper mattis,
              pulvinar dapibus leo. </p>
          </div>
        </div>
        <div class="img-container">
          <img src="/images/team_sitting_basketball_court.jpg" alt="basketball court">
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.bio {
  margin-bottom: 40px;
  .bio-item {
    display: flex;
    justify-content: space-between;
    gap: 20px;
  }
  .img-container {
    background: rgb(0,0,0);
    background: linear-gradient(135deg, $black 0%, $primary 100%);
    padding: 1em;
    img {
      width: 100%;
      filter: brightness(115%) contrast(100%) saturate(0%) blur(0px) hue-rotate(0deg);
    }
  }
}
</style>
