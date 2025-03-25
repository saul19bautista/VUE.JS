<script setup>
import Header from './Header.vue';
import Footer from './Footer.vue';
import Navbar from './Navbar.vue';
import HeroSection from './HeroSection.vue';
import Bootstrap from './Bootstrap.vue';
</script>

<template>

<div id="particles-js"></div> <!-- Este es el contenedor para las partículas -->

  <Header /> <!-- Se usa el componente Header -->

<Navbar/>

<HeroSection />

  <!-- Estructura HTML -->

  <div class="container">
    <div class="section">
      <h2>Descubre Nuestro Paraíso</h2>
      <p>Explora nuestras comodidades de lujo y vive una experiencia única en cada rincón de nuestro hotel.</p>
    </div>
  </div>



<Bootstrap/>
<Footer/> <!-- Se usa el componente Footer -->
</template>

<style scoped>
/* Estilo CSS */ 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
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



.container {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
  text-align: center;
}

.hero-image {
  background-image: url('descarga.jpg');
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

<script>
</script>