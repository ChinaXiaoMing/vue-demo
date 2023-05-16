<template>
  <div class="common-layout">
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>
<script>
export default {
  name: 'hello-world'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.common-layout .el-header {
  background-color: var(--el-color-primary-light-7);
}
.common-layout .el-aside {
  color: var(--el-text-color-primary);
  background: var(--el-color-primary-light-8);
}
.common-layout .el-main {
  color: var(--el-text-color-primary);
  background: var(--el-color-primary-light-9);
}
</style>
