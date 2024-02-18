<script setup lang="ts">
import '../assets/base.css';
defineProps({
  points: Number,
});
</script>

<template>
  <main>
    <p id="score-text">SCORE</p>
    <p id="score-points">{{ points }}</p>
  </main>
</template>

<style>
main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0.5em 0em;
  width: 8rem;
  height: max-content;
  background-color: aliceblue;
  border: none;
  border-radius: 10px;
}
#score-text {
  font-size: 1.2em;
  color: var(--color-score-text);
}
#score-points {
  font-size: 3em;
  font-weight: 700;
  color: var(--color-dark-text);
  margin-top: -15px;
}
</style>
