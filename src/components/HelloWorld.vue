<template>
  <div class="hello">
    <el-container>
      <el-header>
        <el-row>
          <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
          <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
          <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
          <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
          <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
          <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
        </el-row>
</el-header>
    <el-main>Main</el-main>
</el-container>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .el-header, .el-footer {
      background-color: #B3C0D1;
      color: #333;
      text-align: center;
      line-height: 60px;
    }
   .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }
   .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
  }
</style>
