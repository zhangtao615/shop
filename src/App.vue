<template>
  <div id="app">
      <!-- 底部导航栏 -->
      <router-view></router-view>
      <ul class="footer-bar">
        <li class="footer-bar-item">
          <router-link to="/">首页</router-link>
        </li>
        <li class="footer-bar-item">
          <router-link to="/category">分类</router-link>
        </li>
        <li class="footer-bar-item">
          <router-link to="/cart">购物车</router-link>
        </li>
        <li class="footer-bar-item">
          <router-link to="/profile">我的</router-link>
        </li>
      </ul>
  </div>
</template>
<style lang="scss" scoped>
  .footer-bar{
    width: 100%;
    height: 0.8rem;
    font-size: 0.2rem;
    background-color: #eee;
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: fixed;
    bottom: 0;
  }
</style>
