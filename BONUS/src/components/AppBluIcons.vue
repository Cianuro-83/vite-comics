<!-- **************************
HTML
************************** -->
<template>
  <div class="card-box">
    <div class="container">
      <ul class="flex">
        <li class="card-item flex">
          <img
            src="../../public/img/buy-comics-digital-comics.png"
            alt=""
            class="thumb"
          />
          <p class="thumb-description">digital comics</p>
        </li>
        <li class="card-item flex margin-rl">
          <img
            src="../../public/img/buy-comics-merchandise.png"
            alt=""
            class="thumb"
          />
          <p class="thumb-description">dc merchandise</p>
        </li>
        <li class="card-item flex">
          <img
            src="../../public/img/buy-comics-subscriptions.png"
            alt=""
            class="thumb"
          />
          <p class="thumb-description">subscription</p>
        </li>
        <li class="card-item flex margin-rl">
          <img
            src="../../public/img/buy-comics-shop-locator.png"
            alt=""
            class="thumb"
          />
          <p class="thumb-description">comic shop locator</p>
        </li>
        <li class="card-item flex">
          <img
            src="../../public/img/buy-dc-power-visa.svg"
            alt=""
            class="thumb svg"
          />
          <p class="thumb-description">dc power visa</p>
        </li>
      </ul>
    </div>
  </div>
</template>

<!-- **************************
  JAVA SCRIPT
  ************************** -->
<script>
export default {};
</script>

<!-- **************************
  STYLE
  ************************** -->
<style lang="scss" scoped>
.card-box {
  background-color: #0182f9;
  color: white;
  text-transform: uppercase;
}
.container {
  padding: 30px 0;
  font-size: 12px;
}
.thumb {
  width: 25px;
  display: block;
  margin-right: 15px;
}
.svg {
  width: 40px;
}
.flex {
  display: flex;
  align-items: center;
}
.margin-rl {
  margin: 0 30px;
}
li {
  cursor: pointer;
}
</style>
