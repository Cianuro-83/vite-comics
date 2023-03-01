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
  <div class="up-footer"></div>
  <div class="lower-footer">
    <div class="container flex">
      <button>sign up now</button>
      <div class="follow flex">
        <p class="follow-us">follow us</p>
        <ul class="flex">
          <li><img src="../../public/img/footer-facebook.png" alt="" /></li>
          <li class="margin-rl">
            <img src="../../public/img/footer-twitter.png" alt="" />
          </li>
          <li><img src="../../public/img/footer-youtube.png" alt="" /></li>
          <li class="margin-rl">
            <img src="../../public/img/footer-pinterest.png" alt="" />
          </li>
          <li><img src="../../public/img/footer-periscope.png" alt="" /></li>
        </ul>
      </div>
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
  justify-content: space-between;
}
.margin-rl {
  margin: 0 30px;
}
li {
  cursor: pointer;
}
.lower-footer {
  background-color: #303030;
  button {
    line-height: 2rem;
    padding: 5px 10px;
    background-color: #303030;
    color: white;
    text-transform: uppercase;
    border-color: #0182f9;
    font-weight: bold;
    cursor: pointer;
  }
  .follow-us {
    color: #0182f9;
    font-size: 1.3rem;
    margin-right: 30px;
    text-transform: uppercase;
    font-weight: 700;
  }
}
</style>
