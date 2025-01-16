<script setup>
import Sidebar from "./components/Sidebar.vue";
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
  initFlowbite();
})

</script>

<template>
    <div id="app">
      <Sidebar></Sidebar>
    </div>
</template>

<style scoped>

</style>
