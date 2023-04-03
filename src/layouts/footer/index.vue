<template>
  <div class="footer-container">
    Copyright <i
      class="iconfont"
      style="margin: 0 5px"
    >&#xe619;</i> 生源地贷款管理系统 2023
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
@import '../../assets/styles/variables.scss';
.footer-container {
  height: $footerHeight;
  display: flex;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
  border-radius: 3px;
}
</style>
