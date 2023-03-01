<!-- **************************
HTML
************************** -->
<template>
  <header>
    <div class="container flex">
      <div class="logo">
        <img class="logo-img" src="../../public/img/dc-logo.png" alt="" />
      </div>
      <div class="nav">
        <ul class="flex">
          <li>characters</li>
          <li class="margin-around active">comics</li>
          <li>movies</li>
          <li class="margin-around">tv</li>
          <li>games</li>
          <li class="margin-around">collectibles</li>
          <li>video</li>
          <li class="margin-around">fans</li>
          <li>news</li>
          <li class="margin-left">shop</li>
        </ul>
      </div>
    </div>
  </header>
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
// @use "../style/partials/variable" as *;
.container {
  padding-top: 15px;
}
.flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo-img {
  width: 75px;
}
.margin-around {
  margin: 0 10px;
}
.margin-left {
  margin-left: 10px;
}
ul {
  text-transform: uppercase;
  font-weight: bold;
  .margin-around {
    margin: 0 10px;
  }
  .margin-left {
    margin-left: 10px;
  }
}
li.active,
li:hover {
  color: #0182f9;
  cursor: pointer;
}
</style>
