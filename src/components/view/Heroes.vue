<script setup>
import { ref } from 'vue'
</script>

<template>
  <div
    id="carouselExampleDark"
    class="carousel carousel-ligth slide"
    data-bs-ride="carousel"
  >
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleDark"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active" data-bs-interval="10000">
        <img src="src/assets/img/1.jpg" class="img-fluid" alt="..." />
        <div class="carousel-caption d-none d-md-block">
          <h4>Musik Bamboo</h4>
          <p>
            Some representative placeholder content for the first slide.
          </p>
        </div>
      </div>
      <div class="carousel-item" data-bs-interval="2000">
        <img src="src/assets/img/2.jpg" class="img-fluid" alt="..." />
        <div class="carousel-caption d-none d-md-block">
          <h4>Badan Pelayan</h4>
          <p>
            Some representative placeholder content for the second slide.
          </p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="src/assets/img/3.jpg" class="img-fluid" alt="..." />
        <div class="carousel-caption d-none d-md-block">
          <h4>Jadilah Terang Dunia</h4>
          <p>
            Some representative placeholder content for the third slide.
          </p>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselExampleDark"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselExampleDark"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

