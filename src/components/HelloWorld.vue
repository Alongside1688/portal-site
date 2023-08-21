<template>
  <el-row class="mb-4">
    <el-button>Default</el-button>
    <el-button type="primary">Primary</el-button>
    <el-button type="success">Success</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
  </el-row>
  <span class="badge bg-primary">主要</span>
  <span class="badge bg-secondary">次要</span>
  <span class="badge bg-success">成功</span>
  <span class="badge bg-danger">危险</span>
  <span class="badge bg-warning">警告</span>
  <span class="badge bg-info">信息</span>
  <span class="badge bg-light">浅色</span>
  <span class="badge bg-dark">深色</span>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
