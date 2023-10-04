<template>
  <div class="ui card fluid calendar-item">
    <div class="calendar-item-content">
      <div class="date">
        <div>Fri, 25 Nov</div>
        <p>6:30 PM</p>
      </div>
      <h5>Rival 1 vs <span>Pumas Reina Victoria</span></h5>
      <p>Av. de Pío XII, 2, 28016 Madrid</p>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.calendar-item {
  text-align: center;
  h5 {
    font-size: 1.5rem;
    margin: 0;
  }
  span {
    color: $primary;
    text-decoration: underline;
  }
  .date {
    font-style: italic;
  }
  .calendar-item-content {
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding: 2em;
    @include desktop {
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
    }
  }
}
</style>
