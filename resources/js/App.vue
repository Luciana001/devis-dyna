<script setup>
import TestComponent from './components/TestComponent.vue';
import { onMounted } from 'vue';

    onMounted(() => console.log('Hello World'));
</script>

<template>
    <h1>Hello World</h1>
    <TestComponent />
</template>