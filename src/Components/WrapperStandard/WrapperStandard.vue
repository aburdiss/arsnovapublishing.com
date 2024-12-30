<script setup lang="ts">
import HeaderStandard from '../HeaderStandard/HeaderStandard.vue';
import FooterStandard from '../FooterStandard';
</script>

<template>
  <a href="#main_content">Skip to Main Content</a>
  <HeaderStandard></HeaderStandard>
  <main id="main-content">
    <slot></slot>
  </main>
  <FooterStandard></FooterStandard>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
}
.Left-Container {
  display: flex;
}
</style>
