<template>
  <div class="statistic-item">
    <div class="statistic-value">
      <slot name="value"></slot>
    </div>
    <div class="statistic-key">
      <slot name="key"></slot>
    </div>
  </div>
</template>

<style scoped>
.statistic-item {
}

.statistic-value {
  font-weight: bold;
  font-size: large;
}

.statistic-key {
}
</style>
