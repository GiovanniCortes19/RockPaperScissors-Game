<script setup lang="ts">
defineProps({
  author: String,
});
</script>

<template>
  <div class="helloWorld">
    <h1>Hello World: This is {{ author }}</h1>
  </div>
</template>

<style>
.helloWorld {
  border: 1px solid green;
}
</style>
