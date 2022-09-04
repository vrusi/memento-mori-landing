<script setup lang="ts">
import StatisticsComponent from "../components/StatisticsComponent.vue";
import DescriptionComponent from "../components/DescriptionComponent.vue";
import IntermezzoComponent from "../components/IntermezzoComponent.vue";
import MotivationComponent from "../components/MotivationComponent.vue";
</script>

<template>
  <main>
    <StatisticsComponent />
    <div class="spacer"></div>
    <DescriptionComponent />
    <div class="spacer"></div>
    <IntermezzoComponent />
    <div class="spacer"></div>
    <MotivationComponent />
    <div class="spacer"></div>
  </main>
</template>

<style>
.spacer {
  height: 6rem;
  width: 100%;
}
</style>
