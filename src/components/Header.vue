<template>
    <header> 
      <img src="../assets/flor.png" alt="Vue Logo" />
      <div>
        <h1>Hotel Flor del Saber</h1>
        <p>Tu destino de ensueño</p>
      </div>
      <form action="login.html" method="POST">
        <button class="logout-button" type="submit" name="logout">Cerrar sesión</button>
      </form>
    </header>
  </template>
  
  <style scoped>
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
  }
  
  .logout-button:hover {
    background-color: #d35400;
  }
  </style>