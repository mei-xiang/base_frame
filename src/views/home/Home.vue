<template>
  <div>
    我是首页
  </div>
</template>

<script>
export default {}
</script>

<style lang="less" scope>
.home {
  width: 100%;
  // width: 1280px;
  margin: auto;
  padding: 16px 0;
  .header {
    width: 100%;
  }
  .el-header {
    // padding: 0;
  }
  .container {
    padding: 16px 50px 16px 50px;
    .el-aside {
      .el-menu-item.is-active {
        background-color: #42a5f5 !important;
        color: #fff;
      }
      .el-submenu__title:hover {
        background-color: #45b7fe !important;
        color: #fff !important;
      }
      .el-menu-item:hover {
        background-color: #45b7fe !important;
        color: #fff !important;
      }
      .el-menu-item,
      .el-submenu__title {
        height: 38px;
        line-height: 38px;
        margin: 0 0 2px;
        border-bottom: 2px solid #fff;
      }
      .el-menu-item-group__title {
        font-size: 13px;
        line-height: 25px;
        padding: 0 0 0 23px;
        color: #bcbec1;
        margin-left: 0;
      }
      .el-menu-item-group li {
        color: #009cfa;
        border-bottom: none;
      }
      .el-menu-item-group .el-menu-item.is-active {
        color: #009cfa !important;
        background-color: #eef3f6 !important;
      }
      .el-menu-item-group .el-menu-item:hover {
        color: #1e88e5 !important;
        background-color: #eef3f6 !important;
      }
    }
  }
}
</style>
