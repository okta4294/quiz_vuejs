<script setup>

import Button from './Button.vue';
</script>
<template>
  <div class="container py-5">
    <div class="row flex-lg-row-reverse align-items-center d-flex g-5 justify-content-between py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <lottie-player src="https://assets2.lottiefiles.com/packages/lf20_tijmpky4.json"  background="transparent"  speed="1"  style="width: 500px; height: 500px;"  loop controls autoplay></lottie-player>
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">
          Mending Kuliah Di sini<br />
          Ya Deket aja sih
        </h1>
        <p class="lead">
          Ayo bergabung dalam perjalanan pendidikan yang menakjubkan! Mulailah petualanganmu menuju ilmu pengetahuan yang tak terbatas dan kesempatan yang luas dengan bergabung di perguruan tinggi. Temukan bakatmu, kembangkan potensimu, dan raih impianmu melalui kuliah. Bergabunglah dengan kami dan bersama-sama kita bangun masa depan yang gemilang!
        </p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start">
          <Button text="Primary" class="btn-primary btn-lg px-4 me-md-2" />
          <Button text="Default" class="btn-outline-secondary btn-lg px-4" />
        </div>
      </div>
    </div>
  </div>
</template>
