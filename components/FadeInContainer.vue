<template>
  <div class="container">
    <slot></slot>
  </div>
</template>
<style lang="scss" scoped>
.container {
  view-timeline: --container;
  view-timeline-axis: block;
  animation-timeline: --container;
  animation-name: fadeIn;
  animation-range: entry 0% cover 50%;
}
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style>
