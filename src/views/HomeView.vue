<script setup>
import TheWelcome from '../components/TheWelcome.vue'
const name = reactive({name:'mike'});
</script>

<template>
  <main>
    {{ name }}
    <TheWelcome />
  </main>
</template>
