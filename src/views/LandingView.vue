<script setup lang="ts">
import StatisticsComponent from "../components/StatisticsComponent.vue";
import DescriptionComponent from "../components/DescriptionComponent.vue";
import IntermezzoComponent from "../components/IntermezzoComponent.vue";
</script>

<template>
  <main>
    <StatisticsComponent />
    <div class="spacer"></div>
    <DescriptionComponent />
    <div class="spacer"></div>
    <IntermezzoComponent />
  </main>
</template>

<style>
.spacer {
  height: 5rem;
  width: 100%;
}
</style>
