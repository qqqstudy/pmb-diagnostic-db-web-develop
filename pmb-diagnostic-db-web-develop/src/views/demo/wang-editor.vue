<!-- wangEditor富文本编辑器示例 -->
<script setup lang="ts">
import Editor from "@/components/WangEditor/index.vue";

const value = ref("初始内容");
</script>

<template>
  <div class="app-container">
    <el-link
      href="https://github.com/AZU-RDIT/pmb-diagnostic-db-web.git"
      type="primary"
      target="_blank"
      class="mb-[20px]"
      >示例源码 请点击>>>></el-link
    >
    <editor v-model="value" style="height: calc(100vh - 180px)" />
  </div>
</template>
