<template>
  <div class="container about">
    <div class="container d-flex flex-column py-5">
      <div id="carouselControlsBigScreen" class="carouselBigScreen carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselControlsBigScreen" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselControlsBigScreen" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselControlsBigScreen" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active c-item">
            <img src="../assets/images/futbol.jpg" class="d-block w-100 c-img" alt="DISCIPLINAS">
            <div class="carousel-caption bot-0 my-auto">
                <h1 class="display-5 fw-bolder text-capitalize">Disciplinas</h1>
                <p class="fs-5">
                  Vas a poder ver las disciplinas en las que te encontrás inscripto.
                  Además, es posible listar todas las disciplinas que ejercemos en el club.
                </p>
            </div>
          </div>
          <div class="carousel-item c-item">
            <img src="../assets/images/patin.jpg" class="d-block w-100 c-img" alt="ESTADÍSTICAS">
            <div class="carousel-caption bot-0 my-auto">
                <h1 class="display-5 fw-bolder text-capitalize">Estadísticas</h1>
                <p class="fs-5">
                  Podrás consultar las estadísticas relacionadas al club, con diversos
                  tipos de gráficos. 
                </p>
            </div>
          </div>
          <div class="carousel-item c-item">
            <img src="../assets/images/gimnasia.jpg" class="d-block w-100 c-img" alt="PAGOS">
            <div class="carousel-caption bot-0 my-auto">
                <h4 class="display-5 fw-bolder text-capitalize">Pagos</h4>
                <p class="fs-5">
                  Vas a poder ver tus cuotas y el estado de las mismas.
                  Además, podrás registrar tus pagos.  
                </p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselControlsBigScreen" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselControlsBigScreen" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>
</template>


<style>

.c-item {
  height: 640px
}

.c-img {
  height: 100%;
  object-fit: cover;
  filter: brightness(0.6);
}

.carousel-caption p {
  color: white;
  word-break: normal
}
  
</style>
