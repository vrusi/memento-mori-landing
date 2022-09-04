<script setup lang="ts">
import IconHeart from "./icons/IconHeart.vue";
import IconWind from "./icons/IconWind.vue";
import IconCloud from "./icons/IconCloud.vue";
import IconQuote from "./icons/IconQuote.vue";
</script>

<template>
  <div class="flex">
    <div id="motivation-left">
      <div id="motivation-img"></div>
      <div id="quote-box">
        <IconQuote />
        <p id="quote">Life is like a lentil, or you take it or leave it.</p>
      </div>
    </div>
    <div id="motivation-right">
      <div class="motivation-line">
        <i>
          <IconHeart />
        </i>
        <p>Here you can put a cool title for explain something cool</p>
      </div>
      <div class="motivation-line">
        <i>
          <IconWind />
        </i>
        <p>Here you can put a cool title for explain something cool</p>
      </div>
      <div class="motivation-line">
        <i>
          <IconCloud />
        </i>
        <p>Here you can put a cool title for explain something cool</p>
      </div>
    </div>
  </div>
</template>

<style>
#motivation-left {
  width: 50%;
  display: grid;
}

#motivation-img {
  grid-column: 1;
  grid-row: 1;
  background: url("https://images.unsplash.com/photo-1553969546-6f7388a7e07c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=988&q=80");
  height: 30rem;
  width: 25rem;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

#quote-box {
  grid-column: 1;
  grid-row: 1;
  height: 19rem;
  width: 19rem;
  background-color: #22577a;
  border-radius: 10px;
  padding: 2rem;
  padding-right: 4rem;
  margin: auto auto 1rem 15rem;
}

#quote {
  color: #fffeff;
  font-size: 2.5rem;
  margin-bottom: 0;
  margin-top: 1rem;
  line-height: 2.5rem;
}

#motivation-right {
  width: 50%;
  display: flex;
  flex-flow: column;
  justify-content: space-evenly;
  margin-left: 13rem;
}

.motivation-line {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.motivation-line > p {
  font-family: "Gilroy-Bold";
  padding-left: 2rem;
}
</style>
