<script setup lang="ts">
import StatisticsComponent from "../components/StatisticsComponent.vue";
import DescriptionComponent from "../components/DescriptionComponent.vue";
</script>

<template>
  <main>
    <StatisticsComponent />
    <div class="spacer"></div>
    <DescriptionComponent />
  </main>
</template>

<style>
.spacer {
  height: 10rem;
  width: 100%;
}
</style>
