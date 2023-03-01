<!-- **************************
JAVASCRIPT
************************** -->

<script>
// **************************
// IMPORT
// **************************
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";
//********************
// EXPORT
//******************** */
export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
};
</script>

<!-- **************************
HTML
************************** -->
<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<!-- **************************
STYLE
************************** -->
<style lang="scss">
@use "./style/general.scss";
</style>
