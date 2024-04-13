<script setup lang="ts">
// import { ref } from 'vue'

defineProps()

</script>

<template>
  <div class="print-text">你好！我是Sincere Xie.</div>
</template>

<style scoped>
.print-text {
  position: relative;
  color: #fff;
  width: 22ch;
  animation: typing 2s steps(22), blink .5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: monospace;
  font-size: 20px;
  margin-top: 20px;
  font-weight: bold;
}
@keyframes typing {
  from {
    width: 0
  }
}

@keyframes blink {
  50% {
    border-color: transparent
  }
}
</style>
