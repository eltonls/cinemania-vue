<script>
  export default {
    data() {
      return {
        count: 0
      }
    }
  }
</script>

<template>
  <button @click="count++">Bora, clica aí {{ count }}</button>
</template>

<style scoped>
  button {
    font-weight: bold;
    border-radius: 2em;
  }
</style>
