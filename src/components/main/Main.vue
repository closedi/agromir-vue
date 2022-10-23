<template>
  <main>
    <div id="scrollMain" class="px-4 pt-5 my-5 text-center border-bottom">
      <h1 class="display-4 fw-bold">Основная информация</h1>
      <div class="col-lg-6 mx-auto">
        <p class="lead mb-4">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
        <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
          <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">Primary button</button>
          <button type="button" class="btn btn-outline-secondary btn-lg px-4">Secondary</button>
        </div>
      </div>
      <div class="overflow-hidden" style="max-height: 30vh;">
        <div class="container px-5">
          <img src="../../assets/field-md.jpg" class="img-fluid border rounded-3 shadow-lg mb-4" alt="Example image" loading="lazy">
        </div>
      </div>
    </div>

    <Features />

    <div id="scrollPrice" class="px-4 pt-5 my-5 text-center border-bottom">
      <h1 class="display-4 fw-bold">Актуальные цены</h1>
      <div class="col-lg-6 mx-auto">
        <p class="lead mb-4">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
        <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
          <a href="/tests-example.xls" download>
            <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">Скачать прайс</button>
          </a>
        </div>
      </div>
    </div>
  </main>
</template>

<script lang="ts">

import Features from "@/components/main/Features.vue";
import { defineComponent } from "vue";

export default defineComponent({
  components: {
    Features
  }
});
</script>

<style scoped>

</style>