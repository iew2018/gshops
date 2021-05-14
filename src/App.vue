<template>
  <div class="app">
    <FooterGuide v-show="$route.meta.showFooter"></FooterGuide>
    <router-view></router-view>
  </div>
</template>
<script>
  import FooterGuide from './components/FooterGuide/FooterGuide';
  export default {
    components: {
      FooterGuide,
    },
  };
</script>
<style lang='stylus'></style>