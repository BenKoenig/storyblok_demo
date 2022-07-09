<template>
  <div v-editable="blok" class="py-2">
    <h1 class="text-lg text-red-300">{{ blok.name }}</h1>
    <img :src="blok.img.filename" :alt="blok.name"/>
  </div>
</template>
 
<script setup>
defineProps({ blok: Object })
</script>