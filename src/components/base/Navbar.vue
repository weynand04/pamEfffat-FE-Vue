<script setup>
import { ref } from 'vue'
</script>

<template>
    <div class="container">
    <a class="navbar-brand" href="#">BP. PAM</a>
    <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
    >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
        <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#app">Beranda</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#program">Program</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#galery">Galery</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#about">Tentang Kami</a>
        </li>
        </ul>
    </div>
    </div>
</template>