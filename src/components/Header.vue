<template>
  <div>
    <el-row :gutter="20">
      <el-col :span="6">
        <div class="grid-content ep-bg-purple el-row el-col"/>
      </el-col>
      <el-col :span="6" :offset="6"
      >
        <el-icon>
          <WindPower/>
        </el-icon>
        <div class="grid-content ep-bg-purple"
        />
      </el-col>
    </el-row>
    <el-row :gutter="20">
      <el-col :span="12" :offset="6"
      >
        <router-link to="/">Home</router-link>
        <div class="grid-content ep-bg-purple"
        />
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
}

.el-row:last-child {
  margin-bottom: 0;
}

.el-col {
  border-radius: 4px;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
}
</style>