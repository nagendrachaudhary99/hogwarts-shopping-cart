<template>
    <div class="alert">
        Error:
        <slot>Something went Wrong</slot>
    </div>
</template>

<script setup>

</script>

<style scoped>
.alert{
    background-color: #f0c3c0;
    padding: 15px;
    margin:10px 0;
    border: 1px solid #f0c3c0;
    font-family: Arial, Helvetica, sans-serif;
    font-size:14px;
}
</style>