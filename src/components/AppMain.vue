<!-- **************************
HTML
************************** -->
<template>
  <main>
    <figure>
      <img class="jumbotron" src="../../public/img/jumbotron.jpg" alt="" />
    </figure>
    <div class="container">--\\ Content goes here // e3dwedwe d2w3q--</div>
  </main>
</template>

<!-- **************************
JAVA SCRIPT
************************** -->
<script>
import AppHero from "./Apphero.vue";
export default {
  components: {
    AppHero,
  },
};
</script>

<!-- **************************
STYLE
************************** -->
<style lang="scss" scoped>
main {
  background-color: black;
  color: white;
  width: 100%;
  height: 100px;
}
.container {
  font-size: 24px;
  font-weight: bold;
  padding-top: 35px;
}
figure {
  height: 10px;
}
// .jumbotron {
//   width: 100%;
//   height: 100px;
// }
figure {
  border: 2px solid red;
  width: 100%;
  height: 300px;
  background-color: white;
}
</style>
