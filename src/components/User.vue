<template>
    
    <span class="user">
        <span class="name">{{user.name}}</span>
        <span class="handle">{{user.handle}}</span>
    </span>

    </template>
    <script setup>
import { defineProps } from 'vue'
const props = defineProps(['user']);
</script>