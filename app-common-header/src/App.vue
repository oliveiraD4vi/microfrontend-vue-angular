<template>
  <header>
    <h1>Header</h1>
    <h3>This is the Header in Vue</h3>

    <a href="/">
      Rota padrão
    </a>
    <a href="/elevar">
      Rota alternativa
    </a>
  </header>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style scoped>
header {
  border: 5px solid green;
}

header h1 {
  margin: 0;
}
</style>
