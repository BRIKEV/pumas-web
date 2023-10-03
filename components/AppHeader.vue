<template>
  <header class="navbar">
    <div class="image-container">
      <AppLogo />
    </div>
    <nav class="ui large secondary menu">
      <a class="item"><i class="basketball ball icon"></i>Inicio</a>
      <a class="item"><i class="users icon"></i>Sobre nosotros</a>
      <a class="item"><i class="calendar alternate outline icon"></i>Calendario</a>
    </nav>
  </header>
</template>
<style lang="scss" scoped>
.navbar {
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  left: 0;
  right: 0;
  background-color: $white;
  z-index: 9;
  .image-container {
    max-width: 80px;
  }
}
</style>
