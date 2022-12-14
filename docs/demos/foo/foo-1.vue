<template>
  <button @click="clickHandle">测试按钮</button>
</template>
<script lang="ts" setup>
const clickHandle = () => {
  alert('点击测试按钮');
};
</script>
<style scoped>
button {
  background-color: skyblue;
  padding: 12px 20px;
  color: #fff;
  border-radius: 6px;
}
</style>
