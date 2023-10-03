<template>
  <header class="navbar">
    <div class="image-container">
      <NuxtLink to="/">
        <AppLogo />
      </NuxtLink>
    </div>
    <nav class="ui large secondary menu">
      <NuxtLink to="/" class="item hide-xs"><i class="basketball ball icon nav-icon"></i>Inicio</NuxtLink>
      <NuxtLink to="/club" class="item"><i class="users icon nav-icon"></i>Nosotros</NuxtLink>
      <NuxtLink to="/calendario" class="item"><i class="calendar alternate outline icon nav-icon"></i>Calendario</NuxtLink>
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
  @include small-mobile {
    .item.hide-xs {
      display: none;
    }
  }
  @include mobile {
    .nav-icon {
      display: none;
    }
  }
}
</style>
