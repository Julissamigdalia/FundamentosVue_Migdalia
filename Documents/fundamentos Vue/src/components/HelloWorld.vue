<script setup>
</script>

<template>
  <div class="container mt-4">
    <!-- Título centrado -->
    <div class="text-center mb-3">
      <h1 class="fw-bold">MASCOTAS</h1>
    </div>
    

    <!-- Fila de categorías (Gatos y Perros) -->
    <div class="row justify-content-center mb-4">
      <div class="col-md-5">
        <div class="card border-dark">
          <div class="card-header category-header">Gatos</div>
          <div class="card-body">
            <p class="card-text text-center">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
          </div>
        </div>
      </div>

      <div class="col-md-5">
        <div class="card border-dark">
          <div class="card-header category-header">Perros</div>
          <div class="card-body">
            <p class="card-text text-center">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Fila con las tarjetas de mascotas -->
    <div class="row justify-content-center">
      <div class="col-12 col-md-3 d-flex justify-content-center mb-4">
        <div class="card text-center shadow border card-container">
          <div class="card-img-container">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXabC6Q1zrZH-Ii7EPebIJCa4mu-yMso2eLw&s" class="card-img-top img-fluid" alt="Gato">
          </div>
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
            <button class="btn btn-warning">Más información</button>
          </div>
        </div>
      </div>

      <div class="col-12 col-md-3 d-flex justify-content-center mb-4">
        <div class="card text-center shadow border card-container">
          <div class="card-img-container">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXabC6Q1zrZH-Ii7EPebIJCa4mu-yMso2eLw&s" class="card-img-top img-fluid" alt="Perro">
          </div>
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
            <button class="btn btn-warning">Más información</button>
          </div>
        </div>
      </div>

      <div class="col-12 col-md-3 d-flex justify-content-center mb-4">
        <div class="card text-center shadow border card-container">
          <div class="card-img-container">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXabC6Q1zrZH-Ii7EPebIJCa4mu-yMso2eLw&s" class="card-img-top img-fluid" alt="Mascota">
          </div>
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card’s content.</p>
            <button class="btn btn-warning">Más información</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Tarjetas del mismo tamaño */
.card {
  width: 100%;
  max-width: 18rem;
  border-radius: 10px;
}

/* Contenedor de la imagen */
.card-img-container {
  margin-bottom: 10px; /* Separación entre imagen y texto */
}

/* Imágenes del mismo tamaño y centradas */
.card-img-top {
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
}

/* Para asegurarse de que las tarjetas estén centradas en pantallas pequeñas */
.row.justify-content-center {
  display: flex;
  justify-content: center;
}

.col-12 {
  display: flex;
  justify-content: center;
  margin-bottom: 20px; /* Separación entre las tarjetas */
}

/* Cuadro alrededor del texto de Gatos y Perros */
.category-header {
  background-color: #f0f0f0;
  border: 2px solid #000;
  padding: 10px;
  text-align: center;
  font-weight: bold;
  font-size: 1.2rem;
  border-radius: 5px;
}

/* Estilo adicional para las tarjetas */
.card-container {
  background-color: transparent; /* Sin fondo */
  padding: 10px;
  border: 2px solid #000; /* Marco alrededor de cada tarjeta */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

/* Estilo de centrado para el título "MASCOTAS" */
.text-center {
  text-align: center;
  margin: 0 auto;
  width: 100%; /* Asegura que ocupe todo el ancho disponible */
}
</style>
