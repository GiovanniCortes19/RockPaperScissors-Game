<script setup lang="ts">
import WelcomeItem from '@/components/WelcomeItem.vue';
</script>

<template>
  <div class="about">
    <WelcomeItem />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    /* min-height: 100vh; */
    display: flex;
    align-items: center;
    background-color: rgba(195, 195, 195, 0.778);
  }
}
</style>
