<template>
  <div class="title">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "Title",
  data() {
    return {
      title: "La mia prima app con Vue CLI && un Hero Component",
    };
  },
};
</script>

<style lang="scss" scoped>
.title {
  top: 50%;
  left: 50%;
  color: #ffffff;
  max-width: 480px;
  position: absolute;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  transform: translate(-50%, -50%);

  > h1 {
    font-size: 2rem;
    overflow: hidden;
    line-height: 2.5rem;
    text-overflow: ellipsis;
  }
}
</style>
