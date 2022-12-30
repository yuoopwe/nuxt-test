<template>
  <div>Hello</div>
  <div>{{ data }}</div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/GBP");
</script>
