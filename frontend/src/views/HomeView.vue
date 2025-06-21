<template>
  <div class="home-view">
    <h1>欢迎来到南京黍苗科技</h1>
    <p class="subtitle">我们致力于用科技赋能现代农业</p>
    
    <el-row :gutter="20" justify="center" class="card-container">
      <el-col :span="6">
        <el-card shadow="hover">
          <div class="card-content">
            <el-icon :size="40" color="#4169e1"><DataLine /></el-icon>
            <h3>家庭农场优化</h3>
            <p>利用AI模型分析，提供定制化优化方案，提升生产效率。</p>
          </div>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card shadow="hover">
          <div class="card-content">
            <el-icon :size="40" color="#ffd700"><ShoppingCart /></el-icon>
            <h3>农产品电商</h3>
            <p>打造从田间到餐桌的直通平台，体验VR农场，放心购买。</p>
          </div>
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card shadow="hover">
          <div class="card-content">
            <el-icon :size="40" color="#2e8b57"><Document /></el-icon>
            <h3>农业政策服务</h3>
            <p>实时追踪政策动向，智能解读，为您精准推送相关信息。</p>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script setup>
import { DataLine, ShoppingCart, Document } from '@element-plus/icons-vue'
</script>

<style scoped>
.home-view {
  text-align: center;
  padding: 40px 20px;
}
h1 {
  font-size: 2.5rem;
  color: #1e6b52;
  font-family: 'Alibaba PuHuiTi', sans-serif;
  margin-bottom: 10px;
}
.subtitle {
  font-size: 1.2rem;
  color: #606266;
  margin-bottom: 40px;
}
.card-container {
  margin-top: 30px;
}
.card-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 15px;
  min-height: 150px;
}
.card-content h3 {
  margin: 0;
  color: #303133;
}
.card-content p {
  font-size: 0.9rem;
  color: #909399;
  line-height: 1.5;
}
</style> 