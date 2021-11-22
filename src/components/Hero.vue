<template>
  <div class="hero">
    <Title />
    <img src="../assets/jumbo.png" alt="jumbo image" />
  </div>
</template>

<script>
import Title from "./Title.vue";
export default {
  components: { Title },
};
</script>

<style lang="scss" scoped>
.hero {
  width: 100%;
  overflow: hidden;
  max-height: 640px;
  position: relative;

  > img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
}
</style>
