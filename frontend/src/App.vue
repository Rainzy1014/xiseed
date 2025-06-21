<template>
  <el-container class="main-layout">
    <el-header class="header">
      <div class="logo-container">
        <img alt="logo" src="/src/assets/logo.svg" width="32" height="32" />
        <span class="logo-text">南京黍苗科技</span>
      </div>
      <el-menu mode="horizontal" :router="true" :default-active="$route.path" class="menu">
        <el-menu-item index="/">首页</el-menu-item>
        <el-menu-item index="/about">关于我们</el-menu-item>
        <el-menu-item index="/farm-optimization">家庭农场优化</el-menu-item>
        <el-menu-item index="/e-commerce">农产品电商</el-menu-item>
        <el-menu-item index="/policy-service">农业政策服务</el-menu-item>
      </el-menu>
    </el-header>
    <el-main class="main-content">
      <router-view />
    </el-main>
  </el-container>
</template>

<script setup>
</script>

<style>
body {
  margin: 0;
  font-family: 'Noto Sans SC', sans-serif;
  background-color: #f5f9f4;
}

.main-layout {
  height: 100vh;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #ffffff;
  border-bottom: 1px solid #e4e7ed;
}

.logo-container {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo-text {
  font-size: 1.25rem;
  font-weight: bold;
  color: #1e6b52;
  font-family: 'Alibaba PuHuiTi', sans-serif;
}

.menu {
  border-bottom: none;
}

.main-content {
  padding: 24px;
}
</style> 