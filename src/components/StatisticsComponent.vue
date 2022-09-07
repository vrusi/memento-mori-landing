<script setup lang="ts">
import StatisticsItem from "./StatisticsItem.vue";
let statistics = [
  { key: "Lorem ipsum", value: "100%" },
  { key: "Lorem ipsum", value: "50k" },
  { key: "Dolor sit amet", value: "250" },
  { key: "Dolor sit amet", value: "12" },
];
</script>

<template>
  <div class="flex">
    <div class="w-50">
      <h1 id="title">Enjoy this amazing template from a cool guy.</h1>
      <div class="space-between">
        <StatisticsItem v-for="statistic in statistics" :key="statistic.key">
          <template #value>{{ statistic.value }}</template>
          <template #key> {{ statistic.key }}</template>
        </StatisticsItem>
      </div>
    </div>
    <div class="w-50">
      <div id="circle"></div>
    </div>
  </div>
</template>

<style>
#title {
  margin: 12rem auto 4rem auto;
}

#circle {
  width: 25rem;
  height: 25rem;
  border-radius: 100%;
  background-color: rgba(87, 204, 153, 0.1);
  margin: auto;
}
</style>
