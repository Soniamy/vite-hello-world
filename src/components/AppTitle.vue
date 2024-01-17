<script>
export default {
  data() {
    return { count: 0 };
  },
  template: `<div>count is {{ count }}</div>`,
};
</script>

<template>
  <header>
    <h1 class="main-title">{{ title }}La mia prima app con Vite!</h1>
  </header>
</template>

<style scoped>
header {
  padding: 20px;
  background-color: rgb(182, 130, 188);
}
</style>
