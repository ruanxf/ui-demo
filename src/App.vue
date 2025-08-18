<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <div id="app-box">
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>

  <RouterView />
</template>

<style scoped>
#app {
  width: 100vw;
  height: 100vh;
}
</style>
