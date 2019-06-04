<template>
  <div id="app">
    <Datetitle />
    <Painting />
    <Story />
  </div>
</template>

<script>
import Datetitle from '@/components/Datetitle'
import Painting from '@/components/Painting'
import Story from '@/components/Story'
export default {
  name: 'app',
  components: {
    Datetitle,
    Painting,
    Story
  }
}
</script>

<style lang="scss">
@import '@/assets/scss/app.scss';
</style>
