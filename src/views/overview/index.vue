<template>
  <el-container>
    <el-header>Header</el-header>
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-main>Main</el-main>
    </el-container>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script setup lang="ts">
const router1 = useRouter();
const routerJump1 = (name: string) => {
  router1.push({
    name,
  });
};
</script>
