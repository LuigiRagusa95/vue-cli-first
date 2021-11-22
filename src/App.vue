<template>
  <div id="app">
    <Hero />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
export default {
  components: {
    Hero,
  },
};
</script>

<style lang="scss">
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html,
body {
  width: 100%;
  height: 100%;
  font-family: sans-serif;
}

body {
  min-height: 100vh;
}
</style>
