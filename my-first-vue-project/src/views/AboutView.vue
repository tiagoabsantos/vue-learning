<script setup>
import { useFlash } from '@/composables/useFlash';
let { flash } = useFlash();
</script>

<template>
  <div class="about">
    <p>
      <button @click="flash('Yay!', 'It Works on About Page!', 'info')">Click Me</button>
    </p>
  </div>
</template>