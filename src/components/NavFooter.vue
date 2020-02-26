<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt />
      <p>小米商城</p>
    </div>
    <div class="footer-link">
      <a href="https://JeffreyZhang96.github.com" target="_blank">JeffreyZhang</a>
    </div>
    <div class="copyright">
      Copyright
      <span class="domain">JeffreyZhang</span> All Rights Reserved
    </div>
  </div>
</template>

<script>
export default {
  name: "nav-footer"
};
</script>

<style lang="scss">
.footer {
  height: 234px;
  border-top: 4px solid #f60;
  background-color: #333;
  color: #999;
  font-size: 16px;
  text-align: center;
  .footer-logo {
    margin-top: 46px;
    margin-bottom: 31px;
    img {
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }
  }
  .footer-link {
    a {
      color: #999;
      display: inline-block;
    }
    margin-bottom: 13px;
  }
  .copyright {
    .domain {
      color: #f60;
    }
  }
}
</style>