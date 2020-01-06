<template>
  <div class="shoplist">
    <div class="shoplist-header">
      <div class="header-top">
        <div class="top-left">←</div>
        <div class="top-cent">←</div>
        <div class="top-righ">☆</div>
      </div>
      <div class="header-bot">
        <input placeholder="搜索品牌或商品" />
      </div>
    </div>
    <div class="shoplist-main">
      <div class="main-left">
        <li>精选推荐</li>
      </div>
      <div class="main-right">
        <div class="right-box">
          <p>毫无推荐</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang='scss'>
.shoplist {
  width: 100%;
  height: 100%;
  .shoplist-header {
    width: 100%;
    height: 100px;
    .header-top {
      height: 50px;
      display: flex;
      div {
        flex: 1;
        line-height: 50px;
      }
      .top-cent {
        padding: 5px 10px;
        background: #666;
        color: #fff;
        text-align: center;
      }
    }
  }
  .shoplist-main {
    width: 100%;
    display: flex;
    .main-left {
      flex: 1;
    }
    .main-right {
      flex: 4;
    }
  }
}
</style>
