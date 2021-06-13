<template>
  <div class="home">
    <!-- CAROUSEL -->
    <div
      id="carouselExampleIndicators"
      class="container carousel slide p-4 carousel-fade"
      data-bs-ride="carousel"
      
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="2000">
          <img src="../assets/carousel1.png" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>Aquí puede ir un título</h5>
            <p>Aquí puede ir una breve descripción de la imagen...</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="../assets/carousel2.png" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>Aquí puede ir un título</h5>
            <p>Aquí puede ir una breve descripción de la imagen...</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="../assets/carousel3.png" class="d-block w-100" alt="..." />
          <div class="carousel-caption d-none d-md-block">
            <h5>Aquí puede ir un título</h5>
            <p>Aquí puede ir una breve descripción de la imagen...</p>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <!-- CARDS -->
    <div class="container px-4">
      <div class="row row-cols-md-2 row-cols-lg-4 justify-content-center">
        <div class="col-sm py-2"> 
          <div class="card w-100 bg-primary text-white">
            <div class="card-body">
              <h5 class="card-title">TODO PARA TU INVERNADERO</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Doloribus quaerat quia, hic accusantium vel libero architecto
                voluptatum ipsa earum culpa autem.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm py-2">
          <div class="card w-100  bg-danger text-white">
            <div class="card-body">
              <h5 class="card-title">COMPROMETIDOS CON EL SERVICIO</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Doloribus quaerat quia, hic accusantium vel libero architecto
                voluptatum ipsa earum culpa autem.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm py-2">
            <div class="card w-100">
            <div class="card-body  bg-success text-white">
              <h5 class="card-title">ATENCIÓN PROFESIONAL Y PERSONALIZADA</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Doloribus quaerat quia, hic accusantium vel libero architecto
                voluptatum ipsa earum culpa autem.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm py-2">
            <div class="card w-100">
            <div class="card-body  bg-warning text-white">
              <h5 class="card-title">SOLO LAS MEJORES MARCAS</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Doloribus quaerat quia, hic accusantium vel libero architecto
                voluptatum ipsa earum culpa autem.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script></script>
