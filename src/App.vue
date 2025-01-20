<script setup>
const name = "Vue 3";

//metodo -methods
const handleClick = () =>{
  console.log('me diste click')
}

</script>
<template>
  <div>
    <h1>Hola {{ name.toUpperCase() }}</h1>
    <button v-on:click="handleClick">Activame</button>
    <button @click="handleClick">Activame</button>

  </div>
</template>


<style scoped>
h1 {
  color: red;
}
</style>