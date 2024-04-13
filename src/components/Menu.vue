<script setup lang="ts">
import PersonalIcon from './PersonalIcon.vue'
import BlogIcon from './BlogIcon.vue'
import BooksIcon from './BooksIcon.vue'
// import { ref } from 'vue'

defineProps()

</script>

<template>
  <div class="menu">
    <!-- <PersonalIcon /> -->
    <BlogIcon />
    <BooksIcon />
  </div>
</template>
<style scoped>
.menu {
  position: fixed;
  left: 50%;
  bottom: 50px;
  width: 150px;
  height: 70px;
  display: flex;
  padding: 0 20px;
  align-items: center;
  justify-content: space-around;
  background: #fff;
  border-radius: 35px;
  transform: translateX(-50%);
  box-shadow: 0 15px 25px rgba(0, 0, 0, 0.1);
}
</style>
