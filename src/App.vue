<template>
  <el-container class="app">
    <el-header style="background-color: #F7ECD0;">
      <!-- 引入对应组件 -->
      <Header/>
    </el-header>
    <el-container style="height: auto">
      <el-aside style="background-color: #EC9339; width: 200px;">
        <!-- 引入对应组件 -->
        <LeftMenu/>
      </el-aside>
      <el-main style="background-color: #e4dfd7; flex: 1 1 auto;">
        <!-- 引入对应组件 -->
        <router-view/>
      </el-main>
    </el-container>
  </el-container>
</template>

<script>
import Header from "@/components/Header";
import LeftMenu from "@/components/LeftMenu";

export default {
  components: {LeftMenu, Header}
}
</script>

<style>
html, body, #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #2c3e50;*/
  height: auto;
  width: auto;
  margin: 0;
  padding: 0;
}

</style>