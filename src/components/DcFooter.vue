<script>
export default {
  name: "DcFooter",
};
</script>

<template>
  <footer>
    <div class="sites">
      <div class="container_col"></div>
      <div class="logo_bg">
        <img src="../assets/img/dc-logo-bg.png" alt="" />
      </div>
    </div>
    <div class="follow">
      <div class="sign"><button>SIGN-UP NOW!</button></div>
      <div class="social"></div>
    </div>
  </footer>
</template>

<style>
.sites {
  width: 100%;
  height: 370px;
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  & img {
    width: 450px;
    position: absolute;
    left: 1128px;
    top: 360px;
  }
}
.follow {
  width: 100%;
  height: 110px;
  background: var(--dc-gray);
  position: absolute;
}
</style>
