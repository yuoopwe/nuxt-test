<template>
  <div>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi aliquam est
    aliquet laoreet aliquam. Suspendisse porta non dui ut porta. Pellentesque
    eleifend augue non eros venenatis, eleifend facilisis libero egestas.
    Vivamus ultrices ligula ut odio tincidunt, a semper mi commodo. Nulla nisi
    enim, maximus eget odio nec, tincidunt laoreet lacus.
  </div>
  <div>{{ data }}</div>
</template>

<script setup>
const { data } = await useFetch("/api/currency/GBP");
</script>
