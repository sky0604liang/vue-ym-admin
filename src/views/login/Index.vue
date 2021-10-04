<template>

    <div class="login-box">
        登录页

         <el-row>
    <el-button>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </el-row>
    </div>

</template>
<script>
export default {
    name:"login"
}
</script>
<style lang="scss" scoped>
// scoped 针对当前组件有效
.login-box{
    // vh 基于窗口的百分百
    height: 100vh;
    background-color: #344a5f;
}

</style>>