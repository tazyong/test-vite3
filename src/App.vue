<script setup lang="ts">
// 非组件构建错误
import { useFormItem } from '@arco-design/web-vue';
const { eventHandlers } = useFormItem();
</script>

<template>
  <!-- 部分组件不支持按需加载 -->
  <a-range-picker />
</template>
