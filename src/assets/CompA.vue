<template>
    <h2>This is component A</h2>    
    <div style="background-color: lightgreen; padding-left: 13px;">
        <CompB></CompB>
        <CompB></CompB>
    </div>
</template>

<script setup>
    import CompB from './CompB.vue';
</script>

<style scoped>

</style>