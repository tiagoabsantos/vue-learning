<script setup>
import TheWelcome from '@/components/TheWelcome.vue'
import { ref } from 'vue';

let message = ref('Hello, World!');

let doSomething = () => {
  alert('Hi there!');
}
</script>

<template>
  <main>
    <TheWelcome />

    <p>{{ message }}</p>
    <button @click="doSomething">Click me</button>
  </main>
</template>
