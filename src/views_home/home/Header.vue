<template>
  <div class="header-box">
    <div class="header-content">
      <div class="logo">{{ title }}</div>
      <div class="login">
        <el-button type="text">登录</el-button>
        <el-button type="text">免费注册</el-button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    title: {
      type: String,
      default: ''
    }
  }
}
</script>

<style scoped>
  .header-box{
    background: #f9f9f9;
    box-shadow: 0 2px 12px 0 rgba(0,0,0,.1);
  }
  .header-content{
    line-height: 50px;
    width: 1200px;
    margin: 0 auto;
    display: flex;
  }
  .logo{
    font-size: 20px;
    font-weight: bold;
  }
  .login{
    margin-left: auto;
    display: flex;
  }
</style>
