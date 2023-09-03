<script setup>
import { reactive } from "vue";

const state = reactive({ count: 0 });

function increment() {
  state.count++;
}
</script>

<template>
  <h1>{{ state.count }}</h1>
  <button @click="increment()">Increment Count</button>
</template>
