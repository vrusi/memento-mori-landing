<script setup lang="ts">
import IconTrees from "./icons/IconTrees.vue";
import IconHills from "./icons/IconHills.vue";
import IconLeaf from "./icons/IconLeaf.vue";
import IconShell from "./icons/IconShell.vue";
</script>

<template>
  <div class="flex">
    <div class="w-35">
      <div id="desc-img"></div>
    </div>
    <div class="w-65" id="desc-right">
      <h1>Memento Mori, always.</h1>

      <div class="flex">
        <div class="desc-item">
          <i>
            <IconHills />
          </i>
          <h2>Super Title</h2>
          <div>
            From pixel-perfect icons and scalable vector graphics, to full user
            flows and interactive prototypes, Sketch is the perfect place to
            design, create and test.
          </div>
        </div>
        <div class="desc-item">
          <i>
            <IconTrees />
          </i>
          <h2>Super Title</h2>
          <div>
            From pixel-perfect icons and scalable vector graphics, to full user
            flows and interactive prototypes, Sketch is the perfect place to
            design, create and test.
          </div>
        </div>
      </div>
      <div class="flex">
        <div class="desc-item">
          <i>
            <IconLeaf />
          </i>
          <h2>Super Title</h2>
          <div>
            From pixel-perfect icons and scalable vector graphics, to full user
            flows and interactive prototypes, Sketch is the perfect place to
            design, create and test.
          </div>
        </div>
        <div class="desc-item">
          <i>
            <IconShell />
          </i>
          <h2>Super Title</h2>
          <div>
            From pixel-perfect icons and scalable vector graphics, to full user
            flows and interactive prototypes, Sketch is the perfect place to
            design, create and test.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
#desc-right {
  margin: 2rem 0 0 4rem;
}

.desc-item {
  margin: 3rem 3rem 0 0;
}

#desc-img {
  background: url("https://images.unsplash.com/photo-1526716173434-a1b560f2065d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2730&q=80");
  height: 40rem;
  width: auto;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
