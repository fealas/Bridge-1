<template>
    <div class="row h-100">
        <div class="container">
            <h1 class="title">欢迎来到</h1>
            <h1 class="title">现代企业创业决策仿真系统</h1>
            <h2 class="subtitle">——人机对抗版</h2>
        </div>
    </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: calc(100vh - 50px);
  padding: 20px;
  background: linear-gradient(to bottom right, #f0f4f8, #edd4d4);
  font-family: 'Arial', sans-serif;
  text-align: center;
}

.title {
  font-size: 50px;
  color: #333;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
  margin: 10px 0;
  transition: color 0.3s;
}

.title:hover {
  color: #bd5858;
}

.subtitle {
  font-size: 24px;
  color: #666;
  margin: 5px 0;
  padding: 0 10px;
  border-left: 3px solid #bd5858;
  padding-left: 10px;
  transition: color 0.3s, transform 0.3s;
}

.subtitle:hover {
  color: #bd5858;
  transform: scale(1.05);
}
</style>