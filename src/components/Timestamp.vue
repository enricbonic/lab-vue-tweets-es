<template>
  <span class="timestamp">{{timestamp}}</span>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps(['timestamp']);
</script>

<style>

</style>