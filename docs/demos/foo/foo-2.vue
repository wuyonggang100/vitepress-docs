<template>
  <input type="text" v-model="msg" placeholder="请输入" />
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const msg = ref('hello custom component');
</script>

<style scoped>
input {
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 6px 10px;
}
</style>
