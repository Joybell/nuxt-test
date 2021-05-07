<template>
  <div>
    <h1>Nuxt Showcase</h1>
    <el-table :data="tableData">
      <el-table-column prop="name" label="Name" width="120">
      </el-table-column>
    </el-table>
  </div>
</template>

<script>
export default {
  layout: 'showcase',
  data() {
    return {
      tableData: [
        { name: '제이비' },
        { name: '쿠마' },
        { name: '가펠' }
      ]
    }
  }
}
</script>
