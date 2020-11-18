
# 介绍

:::demo

```html
<template>
  <div>
    <el-button>{{btn}}</el-button>
    <el-button type="primary">主要按钮</el-button>
    <el-button type="success">成功按钮</el-button>
    <el-button type="info">信息按钮</el-button>
    <el-button type="warning">警告按钮</el-button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      btn: '按钮'
    };
  },
  mounted() {},
}
</script>
```
:::