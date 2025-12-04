<script setup>
import { counter } from '@/store/counterStorage';
</script>

<template>
  <div class="about">
    <p>
      About Page. The current count is {{ counter.count }}
    </p>
  </div>
</template>