<script setup>
const name = 'Nicolas con texto dinamico esto se llama interpolacion de texto tambien conocido como bigotes o mustache';
const arrayFrutas = [
  {
    id: 1,
    name: 'Manzana',
    color: 'red',
    price: '$1500'
  },
  {
    id: 2,
    name: 'Pera',
    color: 'green',
    price: '$2000'
  },
  {
    id: 3,
    name: 'Banana',
    color: 'yellow',
    price: '$3000'
  }
];

</script>

<template>
  <h1>Hola {{ name.toUpperCase() }}</h1>
  <ul>
    <li v-for="fruta in arrayFrutas" :key="fruta.id">{{ fruta.name }}, {{ fruta-price }}</li>
  </ul> 
</template>