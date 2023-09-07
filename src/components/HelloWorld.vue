<script setup lang="ts">
defineProps<{ msg: string }>()

const hi = (msg: string) => {
  alert(msg)
}
</script>

<template>
  <h1 class="hello">{{ msg }}</h1>
  <div class="btn-container">
    <button class="btn" @click="hi('Hello User!')">CLICK HERE!</button>
  </div>
</template>

<style scoped lang="scss">
@import '../../scss/style.scss';
.read-the-docs {
  color: #888;
}
</style>
