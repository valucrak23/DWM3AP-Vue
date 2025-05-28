<script setup>
import Titulo from '../components/Titulo.vue'
import Template from '../components/Template.vue'
</script>
<template>
  <Titulo texto="holiwis" />
  <Template>
    <template #parrafo>
      <p>Esto es solo el parrafo</p>
    </template>
    <p>tu mami</p>
  </Template>
</template>
