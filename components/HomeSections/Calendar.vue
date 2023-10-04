<template>
  <section class="ui container calendar">
    <h2 class="ui title">Próximos partidos</h2>
    <p>Estos van a ser los siguientes partidos de Pumas.</p>
    <CalendarItem />
    <CalendarItem />
    <CalendarItem />
    <NuxtLink to="/calendario">
      <button class="ui green button">
        <i class="calendar alternate outline icon nav-icon"></i>
        Calendario completo
      </button>
    </NuxtLink>
  </section>
</template>
<style lang="scss" scoped>
.calendar {
  text-align: center;
  margin-bottom: 5em;
  .ui.green.button {
    margin-top: 1.5em;
    font-size: 1.2rem;
    background-color: $primary;
  }
}
</style>
