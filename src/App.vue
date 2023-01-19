<script>
// javascript
import AppTitle from './components/Title.vue';
import AppBanner from './components/Banner.vue';
export default {
  data() {
    return {}
  },
  components: {
    AppTitle: AppTitle,
    AppBanner: AppBanner
  }
}
</script>

<template>
  <!-- html -->
  <div>
    <AppTitle></AppTitle>
    <AppBanner></AppBanner>
  </div>
</template>

<style>
/* css */
div {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>