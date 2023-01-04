<template>
  <div class="app">
    <Sidebar />
    <RouterView />
  </div>
</template>
<script setup>
import Sidebar from "@/components/Sidebar.vue";
</script>
<style>
.app {
  display: flex;
  
}

</style>