<script setup>
// Métodos
</script>

<template>
  <!-- Estructura HTML -->
  <h1>Hola mundo</h1>
  <div class="contenedor">
    <img src="../assets/til.jpeg" alt="Vue Logo" />
    <button class="btn">Hola, soy un botón</button>
  </div>
  <p class="texto">HOLAAAAAAA A TODOS COMO ESTAN CHIC@.</p>
</template>

<style scoped>
/* Estilo CSS */ 
h1 {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 50px;
    color: red;
    text-align: center;
}

.contenedor {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px; 
}

.btn {
    background-color: blue;
    color: white;
    border: none;
    cursor: pointer;
    padding: 10px;
    font-size: 16px;
    border-radius: 5px;
}

.texto {
    font-size: 18px;
    color: white;
    margin-top: 10px;
    text-align: center;
}
</style>
