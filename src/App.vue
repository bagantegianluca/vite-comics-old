<script>
import AppHeader from "/src/components/AppHeader.vue";
import AppMain from "/src/components/AppMain.vue";
import AppFooterTop from "/src/components/AppFooterTop.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
  },
};
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooterTop></AppFooterTop>

  <footer>
    <div class="footer-bottom">Test</div>
  </footer>
</template>

<style scoped>
.footer-bottom {
  position: relative;
  z-index: 1000;
  background: var(--dc-comics-l-dark);
  min-height: 110px;
}
</style>
