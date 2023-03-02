<!-- **************************
JAVASCRIPT
************************** -->

<script>
// **************************
// IMPORT
// **************************
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
//********************
// EXPORT
//******************** */
export default {
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<!-- **************************
HTML
************************** -->
<template>
  <AppHeader />
  <AppFooter />
</template>

<!-- **************************
STYLE
************************** -->
<style lang="scss">
@use "./style/general.scss";
</style>
