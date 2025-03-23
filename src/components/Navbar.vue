<script setup>
</script>

<template>
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
</template>

<style scoped>
nav {
  background-color: #34495e;
  padding: 15px 0;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

nav a {
  color: #ecf0f1;
  text-decoration: none;
  padding: 12px 20px;
  font-size: 1.1rem;
  transition: all 0.3s ease;
}

nav a:hover {
  background-color: #e67e22;
  color: #fff;
  border-radius: 5px;
}

</style>