<!-- **************************
HTML
************************** -->
<template>
  <!-- <li class="card">
    <img :src="thumb.comics" alt="" />
  </li> -->
</template>

<!-- **************************
JAVA SCRIPT
************************** -->
<script>
export default {
  props: {
    comics: {
      type: Object,
      required: true,
    },
  },
};
</script>
<!-- **************************
STYLE
************************** -->
<style lang="scss" scoped></style>
