<template>
  <div>
    <el-row :gutter="0">
      <el-col :span="6">
        <div style="margin: auto; height: auto">
          <el-icon>
            <WindPower/>
          </el-icon>
          <div>
            &nbsp; 我的小站
          </div>
        </div>
      </el-col>
      <el-col :span="12" :offset="6">
        <div style="margin: auto; height: auto">
          <router-link to="/">Home</router-link>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.el-row {
  margin-bottom: 20px;
  height: 100%;
}

.el-row:last-child {
  margin-bottom: 0;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
</style>