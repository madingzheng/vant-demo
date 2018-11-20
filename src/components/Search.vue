<template>
  <div class="search-all">
    <div class="search">
      <i class="iconfont icon-search"></i>
      <input class="input" type="text" placeholder="搜索">
    </div>
  </div>
</template>
<script>
export default {
  name: 'Search'
}
</script>
<style lang="less">
.search-all {

  .search {
  position: relative;
  width: 351px;
  height: 34px;
  background-color: #f2f3f7;
  border-radius: 24px;
  margin: 12px auto;

    .icon-search {
      position: absolute;
      left: 30px;
      font-size: 30px;
      top: 1px;
    }

    .input {
      widows: 250px;
      position: absolute;
      background-color: #f2f3f7;
      font-size: 15px;
      border: 0;
      outline: none;
      left: 65px;
      top: 6px;
    }
  }
}
</style>

