<script setup>
import { ref } from 'vue'
</script>

<template>
    <div class="container">
        <div class="row justify-content-center text-center">
          <div class="col-6 mb-4 mt-4" data-aos="fade-up">
            <form>
              <h2>Berlangganan</h2>
              <p>Untuk mendapatkan informasi terbaru dari PAM EFFATA</p>
              <div class="d-flex w-100 gap-2">
                <label for="newsletter1" class="visually-hidden"
                  >Email address</label
                >
                <input
                  id="newsletter1"
                  type="text"
                  class="form-control"
                  placeholder="Email address"
                />
                <button class="btn btn-dark" type="button">Subscribe</button>
              </div>
            </form>
          </div>
        </div>
        <div class="row text-center text-black border-top">
          <div class="col">
            Created by
            <a href="https://github.com/weynand04" class="text-black fw-bold"
              >Weynand</a
            >
          </div>
        </div>
    </div>
</template>