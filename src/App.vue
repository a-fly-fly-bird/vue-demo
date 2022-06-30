<template>
  <div class="common-layout">
    <el-container>
      <el-header>
        <!-- 引入对应组件 -->
        <Header />
      </el-header>
      <el-container>
        <el-aside width="200px">
          <!-- 引入对应组件 -->
          <LeftMenu />
        </el-aside>
        <el-main>
          <!-- 引入对应组件 -->
          <router-view/>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import Header from "@/components/Header";
import LeftMenu from "@/components/LeftMenu";
export default {
  components: {LeftMenu, Header}
}
</script>

<style>
</style>