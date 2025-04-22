<template>

    <div style="background-color: lightblue;">
        <h2>this is component B</h2>
        {{ message }}
        <button @click="updateMessage">Update message</button>
    </div>
</template>

<script setup>
import { inject } from 'vue';

let {message, updateMessage} = inject("msg");
</script>

<style scoped>
</style>