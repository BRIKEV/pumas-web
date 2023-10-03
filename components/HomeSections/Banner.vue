<template>
  <section class="banner">
    <div class="overlay"></div>
    <div class="info">
      <h1 class="ui inverted header">
        Bienvenidos a la Página Oficial de los Pumas <i class="basketball ball icon"></i>
      </h1>
      <h2>Club de baloncesto desde el 2010</h2>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.banner {
  position: relative;
  height: 40vh;
  color: $white;
  background: rgb(0,0,0);
  background: radial-gradient(circle, $black 0%, $primary 100%);
  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    opacity: 0.4;
    background-image: url('/images/team_court_compressed.avif');
    background-size: cover;
  }
  .info {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    z-index: 2;
    position: relative;
    height: 100%;
  }
}
</style>
