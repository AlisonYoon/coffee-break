<template>
  <div id="app">
    <div id="js-today">
      <Story/>
    </div>
    <Painting/>
  </div>
</template>

<script>
import Painting from "@/components/Painting";
import Story from "@/components/Story";
export default {
  name: "app",
  components: {
    Painting,
    Story
  }
};
</script>

<style lang="scss">
@import "@/assets/scss/app.scss";
</style>
