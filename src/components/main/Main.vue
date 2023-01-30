<template>
  <main class="container mt-5">
    <About />
    <div id="scrollPrice" class="px-4 pt-5 my-5 text-center border-bottom">
      <h1 class="display-4 fw-bold">Актуальные цены</h1>
      <div class="col-lg-6 mx-auto">
        <p class="lead mb-4">Здесь Вы можете скачать прайс в формате .xls</p>
        <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
          <a href="/tests-example.xls" download>
            <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">Скачать прайс</button>
          </a>
        </div>
      </div>
    </div>

    <Contacts/>
  </main>
</template>

<script lang="ts">

import Features from "@/components/main/Features.vue";
import { defineComponent } from "vue";
import About from "@/components/About.vue";
import Contacts from "@/components/Contacts.vue";

export default defineComponent({
  components: {
    Contacts,
    About,
    Features
  }
});
</script>

<style scoped>

</style>