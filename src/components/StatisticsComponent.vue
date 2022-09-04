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
  <div id="statistics-wrapper">
    <div id="left">
      <h1 id="title">Enjoy this amazing template from a cool guy.</h1>
      <div id="statistic-items-wrapper">
        <StatisticsItem v-for="statistic in statistics" :key="statistic.key">
          <template #value>{{ statistic.value }}</template>
          <template #key> {{ statistic.key }}</template>
        </StatisticsItem>
      </div>
    </div>
    <div id="right">
      <div id="circle"></div>
    </div>
  </div>
</template>

<style>
#statistics-wrapper {
  display: flex;
}

#title {
  font-family: "Gilroy-Bold";
  margin: 8rem auto 4rem auto;
  font-size: 3rem;
  line-height: 3rem;
}

#left {
  width: 50%;
}
#right {
  width: 50%;
  margin: auto auto 0 auto;
}

#statistic-items-wrapper {
  display: flex;
  justify-content: space-between;
}

#circle {
  width: 20rem;
  height: 20rem;
  border-radius: 100%;
  background-color: rgba(87, 204, 153, 0.1);
  margin: auto;
}
</style>
