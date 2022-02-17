<template>
  <h1>Bonjour <span v-html="name"></span></h1>
  <!-- Remarquez la différence avec v-text : -->
  <div>{{ name }}</div>
</template>

<script setup lang="ts">
const name = '<i>Jean</i>';
</script>

<style></style>
