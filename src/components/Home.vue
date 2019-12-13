<template>
  <div>
    <h1>Home Page</h1>
    <h3 class='less'><span>Less</span></h3>
    <span class="import-less">外部引入less</span>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style lang='less'>
  @import './index.less';
  .less {
    span {
      font-size: 22px;
      font-weight: 700;
      color: #f10215;
    }
  }
</style>
