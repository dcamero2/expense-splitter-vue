<template>
  <main class="card">
    <slot />
  </main>
</template>

<style scoped>
.card {
  width: min(600 px, 100%);
  background: #e7e7ec;
  padding: 18px;
  border-radius: 16px;
  box-shadow: 0 10px 24px rgba(10, 10, 32, 0.2);
}
</style>