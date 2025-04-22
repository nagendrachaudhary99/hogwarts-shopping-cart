<template>
  <div>
    <BaseLayout>
      <template v-slot:header>
        <h1>Header</h1>
      </template>


      <template v-slot:main>
        <h1>Main</h1>
        <p>Something else too</p>
      </template>


      <template v-slot:footer>
          <h1>Footer</h1>
      </template>
    </BaseLayout> 
  </div>
</template>

<script setup>
import BaseLayout from './BaseLayout.vue';
</script>

<style scoped>

</style>