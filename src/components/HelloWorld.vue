<script setup>
// Métodos
</script>

<template>
  <!-- Estructura HTML -->
  <h1>Hola mundo</h1>
  <div class="contenedor">
    <img src="../assets/til.jpeg" alt="Vue Logo" />
    <button class="btn">Hola, soy un botón</button>
  <div id="particles-js"></div> <!-- Este es el contenedor para las partículas -->

  <header> 
    <img src="../assets/flor.png" alt="Vue Logo" />
    <div>
      <h1>Hotel Flor del Saber</h1>
      <p>Tu destino de ensueño suavizante</p>
    </div>
    <form action="login.html" method="POST">
      <button class="logout-button" type="submit" name="logout">Cerrar sesión</button>
    </form>
  </header>


  <nav>
    <a href="registros_clientes.php">Registrar Cliente</a>
    <a href="registros_habitaciones.php">Registrar Habitaciones</a>
    <a href="registro_checkin.php">Check-In</a>
    <a href="registro_checkout.php">Check-Out</a>
    <a href="registros_empleados.php">Empleados</a>
    <a href="registro_facturas.php">Facturas</a>
    <a href="cliente_reservaciones.php">Reservaciones</a>
    <a href="habitaciones.php">Habitaciones</a>
  </nav>

  <div class="container">
    <div class="hero-image">
      <h1>Bienvenido a Hotel Flor del Saber donde el privilegio eres tú</h1>
    </div>

    <div class="section">
      <h2>Descubre Nuestro Paraíso</h2>
      <p>Explora nuestras comodidades de lujo y vive una experiencia única en cada rincón de nuestro hotel.</p>
    </div>
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
