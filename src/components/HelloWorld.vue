<script setup></script>

<template>
  <!-- Estructura HTML -->
  <div id="particles-js"></div>
  <!-- Este es el contenedor para las partículas -->

  <header>
    <img src="../assets/flor.png" alt="Vue Logo" />
    <div>
      <h1>Hotel Flor del Saber</h1>
      <p>Tu destino de ensueño</p>
    </div>
    <form action="login.html" method="POST">
      <button class="logout-button" type="submit" name="logout">
        Cerrar sesión
      </button>
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

    <div class="row mt-5">
      <div class="col-md-4">
        <div class="card" style="width: 18rem">
          <img src="https://imgs.search.brave.com/MrC3IUGLKbHdv5ng-cIQ6mavCtaHnJ2ncwukVsdSiAE/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly90My5m/dGNkbi5uZXQvanBn/LzAwLzYyLzU5Lzcw/LzM2MF9GXzYyNTk3/MDM1X2tKVGtTUFpt/OVAxME9HZnBrV0RY/NWlIbEJ5YXJ1TVVW/LmpwZw" 
          class="card-img-top" alt="..." />
          <div class="card-body">
            <p class="card-text text-center">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <button class="btn btn-warning">Mas Informacion</button>
          </div>
          <div class="col-md-4">
        <div class="card" style="width: 18rem">
          <img src="https://imgs.search.brave.com/SdPT6QcHZeL6ra3eU8PD9vkhD-UcBwAVrXC4FLsiy78/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvNjQw/MzQ0NTg4L3Bob3Rv/L2hvdGVsLXN1aXRl/LWluLXRoZS12aW5l/eWFyZHMtaW4tY2hp/bGUuanBnP3M9NjEy/eDYxMiZ3PTAmaz0y/MCZjPWU5TmNHVER2/aUxlcjNFRmR6Z3pr/UVQtNUhhYjBSRG84/aTZNdk01T1U1SVE9" 
          class="card-img-top" alt="..." />
          <div class="card-body">
            <p class="card-text text-center">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <button class="btn btn-warning">Mas Informacion</button>
          </div>
          <div class="col-md-4">
        <div class="card" style="width: 18rem">
          <img src="https://imgs.search.brave.com/6jHaN2RGYRwEv0QJK2Lp2A-82QM1UcaQQwMVcojVdvg/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5pc3RvY2twaG90/by5jb20vaWQvMTQy/ODA5MTcyMy9lcy9m/b3RvL2FzaXN0ZW50/ZS1kZS1ob3RlbC1j/b24tZXF1aXBhamUt/ZW4tZWwtdmVzdCVD/MyVBRGJ1bG8uanBn/P3M9NjEyeDYxMiZ3/PTAmaz0yMCZjPXhH/Nk1YTHNjdTloaWJH/TGM4TkdPYmVrWWl1/bGJYRndqSVNoa2Rw/Yy1NeHM9"
          class="card-img-top" alt="..." />
          <div class="card-body">
            <p class="card-text text-center">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <button class="btn btn-warning">Mas Informacion</button>
          </div>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>Descubre Nuestro Paraíso</h2>
      <p>
        Explora nuestras comodidades de lujo y vive una experiencia única en
        cada rincón de nuestro hotel.
      </p>
    </div>
  </div>
</template>

<style scoped>
/* Estilo CSS */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Roboto", sans-serif;
  background-color: #2c3e50;
  color: #ffffff;
  line-height: 1.6;
}

#particles-js {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
}

header {
  background: linear-gradient(to right, #34495e, #2c3e50);
  padding: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  position: relative;
}

header img {
  max-width: 150px;
  height: auto;
  margin-right: 20px;
}

header h1 {
  font-size: 2.5rem;
  font-weight: 700;
}

header p {
  font-size: 1.2rem;
  margin-top: 10px;
  font-weight: 300;
}

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

.container {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
  text-align: center;
}

.hero-image {
  background-image: url("descarga.jpg");
  background-size: cover;
  background-position: center;
  height: 400px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  position: relative;
  box-shadow: inset 0 0 0 1000px rgba(0, 0, 0, 0.3);
}

.hero-image h1 {
  font-size: 3rem;
  font-weight: 700;
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
}

.section {
  margin-top: 40px;
  padding: 30px;
  background-color: #34495e;
  border-radius: 10px;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.section p {
  font-size: 1.1rem;
  margin-bottom: 30px;
}

footer {
  background-color: #34495e;
  padding: 20px;
  text-align: center;
  color: #ecf0f1;
  font-size: 1rem;
  border-top: 3px solid #e67e22;
}

footer p {
  margin: 0;
}

.logout-button {
  position: absolute;
  top: 20px;
  right: 20px;
  padding: 10px 20px;
  background-color: #e67e22;
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  text-decoration: none;
}

.logout-button:hover {
  background-color: #d35400;
}
</style>

<script></script>
