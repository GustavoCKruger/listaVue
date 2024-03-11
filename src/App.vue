<script setup>
import { ref } from 'vue';

const cidades = ref(['São Paulo',
  'Rio de Janeiro',
  'Belo Horizonte',
  'Salvador',
  'Fortaleza',
  'Curitiba',
  'Manaus',
  'Recife',
  'Porto Alegre',
  'Brasília'].sort())

</script>

<template>
  <ul>
    <li v-for="(item, index) in cidades" :key="index">{{ item }}</li>
  </ul>
</template>

<style scoped></style>
