<template>
  <div id="main-background" class="w-screen h-screen flex flex-col text-white">
    <div class="flex flex-grow justify-center items-center">
      <div class="transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-125">
        <h1 class="text-3xl md:text-5xl lg:text-6xl text-shadow-lg font-display">Comming Soon!</h1>
      </div>
    </div>
    <footer
      class="flex flex-col flex-shrink justify-center items-center text-shadow text-lg md:text-xl lg:text-2xl font-sans font-medium"
    >
      <div class="flex flex-row">
        <div class="font-bold">Business:&ensp;</div>
        <div class="transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110 hover:underline">
          <a href="mailto:enterprise@elixir.red">enterprise@elixir.red</a>
        </div>
      </div>
      <div class="flex flex-row">
        <div class="font-bold">Sales:&ensp;</div>
        <div class="transition duration-500 ease-in-out transform hover:-translate-y-1 hover:scale-110 hover:underline">
          <a href="mailto:shop@elixir.red">shop@elixir.red</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  components: {},
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#main-background {
  background: rgb(18, 0, 120);
  background: linear-gradient(
    326deg,
    rgba(18, 0, 120, 1) 0%,
    rgba(254, 205, 26, 1) 29%,
    rgba(157, 1, 145, 1) 60%,
    rgba(253, 58, 105, 1) 95%
  );
}
</style>
