<script setup>
import Titulo from '../components/Titulo.vue'
import Template from '../components/Template.vue'
</script>
<template>
  <Titulo texto="holiwis" />
  <Template>
    <template #parrafo>
      <p class="animate__animated animate__bounceInUp">En el mapa no se ve</p>
    </template>
    <p class="animate__animated animate__rubberBand">Chi chi chi le le le</p>
  </Template>
</template>
