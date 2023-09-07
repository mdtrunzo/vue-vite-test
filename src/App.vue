<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template class="bg">
  <div>
    <a href="https://savaslabs.com" target="_blank">
      <img
        src="https://savaslabs.com/themes/custom/savas_2023/logo.svg"
        class="logo"
        alt="Savas Labs Logo"
      />
    </a>
  </div>
  <HelloWorld msg="Hello World!" />
</template>

<style scoped lang="scss">
.logo {
  height: 6em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
