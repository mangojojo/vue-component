<template>
  <div class="warning-box">
    <h1>404</h1>
    <p>抱歉，你访问的页面不存在</p>
    <router-link to="/">返回首页</router-link>
  </div>
</template>

<script>
export default {
  name: "warning"
};
</script>

<style scoped lang="scss">
.warning-box {
  > h1 {
    margin-bottom: 24px;
    color: #434e59;
    font-weight: 600;
    font-size: 72px;
    line-height: 72px;
  }
  > p {
    margin-bottom: 16px;
    color: rgba(0, 0, 0, 0.45);
    font-size: 20px;
    line-height: 28px;
  }
  > a {
    display: block;
    color: #fff;
    padding: 9px 6px;
    background: #7d5cf3;
    width: 25%;
    margin: 0 auto;
    border-radius: 5px;
  }
}
</style>

