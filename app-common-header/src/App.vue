<template>
  <header>
    <h1>Header</h1>
    <h3>This is the Header in Vue</h3>

    <button @click="navigateToUrl('/')">Home</button>
    <button @click="navigateToUrl('/product')">Produto</button>
  </header>
</template>

<script setup>
import { navigateToUrl } from "single-spa";
</script>

<style scoped>
header {
  border: 5px solid green;
}

header h1 {
  margin: 0;
}
</style>
