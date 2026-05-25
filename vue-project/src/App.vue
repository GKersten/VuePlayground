<script setup lang="ts">
const message = "Vue";
const copyRightYear = new Date().getFullYear();
</script>

<template>
  <div class="page-wrapper">
    <main>
      <h1>hello world, {{ message }}</h1>
    </main>
    <footer>
      <p>Copyright {{ copyRightYear }}</p>
    </footer>
  </div>
</template>

<style scoped>
.page-wrapper {
  display: flex;
  flex-direction: column;
  min-height: calc(100vh - 4rem);
}
main {
  flex: 1;
}
h1 {
  font-weight: bold;
  text-align: center;
  color: red;
}
footer {
  text-align: center;
  margin-top: auto;
  padding: 1rem 0;
}
</style>
