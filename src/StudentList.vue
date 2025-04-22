<template>
    <div>
      <ul>
        <li v-for="student in list" :key="student.id">
            <slot :stu="student">
                {{ student.name }}
            </slot>
        </li>
      </ul>
    </div>
  </template>
  
  <script setup>
    defineProps(['list'])
  </script>
  
  <style  scoped>
  
  </style>