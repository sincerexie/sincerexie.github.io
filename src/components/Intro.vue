<script setup lang="ts">
import Menu from './Menu.vue'
import PrintText from './PrintText.vue'
// import { ref } from 'vue'

defineProps()

</script>

<template>
  <div class="container">
    <img class="avatar" src="https://avatars.githubusercontent.com/u/6058689?v=4" />
    <PrintText />
    <Menu />
  </div>
</template>

<style scoped>
.container {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  padding-top: 40px;
}
.avatar {
  position: relative;
  width: 100px;
  height: 100px;
  border-radius: 100%;
  overflow: hidden;
}
</style>
