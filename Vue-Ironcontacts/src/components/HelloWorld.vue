<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})
const count = ref(0)
</script>
<template>
  <h1>{{ msg }}</h1>
  <p>
    <a href="https://code.visualstudio.com/" target="_blank"></a>
    <a href="https://github.com/johnsoncodehk/volar" target="_blank"></a></p>
  <p><a href="https://vitejs.dev/guide/features.html" target="_blank"></a>
  <a href="https://v3.vuejs.org/" target="_blank"></a></p>
  <button type="button" @click="count++">{{ count }}</button>
  <p><code></code></p>
</template>
<style>
a {
  color: #e948db;
}
</style>
