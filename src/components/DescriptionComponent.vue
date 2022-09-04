<script setup lang="ts">
import IconTrees from "./icons/IconTrees.vue";
import IconHills from "./icons/IconHills.vue";
import IconLeaf from "./icons/IconLeaf.vue";
import IconShell from "./icons/IconShell.vue";
</script>

<template>
  <div class="flex">
    <div id="desc-left">
      <img
        src="https://images.unsplash.com/photo-1526716173434-a1b560f2065d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2730&q=80"
        alt="Zen image"
      />
    </div>
    <div id="desc-right">
      <h1>Memento Mori, always.</h1>

      <div class="flex">
        <div class="description-item">
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
        <div class="description-item">
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
        <div class="description-item">
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
        <div class="description-item">
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
img {
  height: auto;
  width: 100%;
}

#desc-left {
  width: 35%;
}

#desc-right {
  width: 65%;
  margin: 2rem 0 0 4rem;
}

.description-item {
  margin: 3rem 3rem 0 0;
}
</style>
