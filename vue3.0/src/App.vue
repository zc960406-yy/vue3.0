<template>
  <div class="sn">
    <div class="left">
      <span>
        <span class="iconfont icon-shujucaiji"></span>
      </span>
      <div class="top">left-top</div>
      <div class="bottom">left-bottom</div>
    </div>
    <div class="right">
      <div class="top">right-top</div>
      <div class="bottom">right-bottom</div>
    </div>
  </div>
</template>

<script lang="ts"></script>
<style lang="scss" scoped>
@import "./style/css/reset.scss";
@import "assets/font/iconfont.css";
.sn {
  display: flex;
  justify-content: space-between;
  .left {
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    font-size: 30px;
  }
}
</style>
