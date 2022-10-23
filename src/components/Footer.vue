<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
});
</script>

<template>
  <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
    <div class="col-md-4 d-flex align-items-center">
      <span class="text-muted">© 2022 ООО Агромир</span>
    </div>

    <ul class="nav col-md-6 justify-content-end list-unstyled d-flex gap-1">
      <li class="ms-3 d-flex">
        <a class="text-muted" href="#">
         <i class="bi bi-instagram"></i>
          <div class="d-inline-block px-1">Instagram</div>
        </a>
      </li>
      <li class="ms-3 d-flex">
        <a class="text-muted" href="#">
          <i class="bi bi-telegram"></i>
          <div class="d-inline-block px-1">Telegram</div>
        </a>
      </li>
      <li class="ms-3 d-flex">
        <a class="text-muted" href="#">
          <i class="bi bi-whatsapp"></i>
          <div class="d-inline-block px-1">Whatsapp</div>
        </a>
      </li>
    </ul>
  </footer>
</template>
