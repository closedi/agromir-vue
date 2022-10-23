<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
})
</script>

<template>
  <h2 class="display-4 fw-bold text-center" id="scrollItems">Средства защиты растений</h2>
  <div class="row g-4 py-5 row-cols-1 row-cols-lg-3 border-bottom">
    <div class="feature col">
      <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3 rounded">
        <i class="bi-people p-2" style="font-size: 24px"></i>
      </div>
      <h3 class="fs-2">Гербициды</h3>
      <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
      <a href="#" class="icon-link d-inline-flex align-items-center">
        Call to action
        <svg class="bi" width="1em" height="1em"><use xlink:href="#chevron-right"></use></svg>
      </a>
    </div>
    <div class="feature col">
      <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3 rounded">
        <i class="bi-people p-2" style="font-size: 24px"></i>
      </div>
      <h3 class="fs-2">Инсектициды</h3>
      <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
      <a href="#" class="icon-link d-inline-flex align-items-center">
        Call to action
        <svg class="bi" width="1em" height="1em"><use xlink:href="#chevron-right"></use></svg>
      </a>
    </div>
    <div class="feature col">
      <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3 rounded">
        <i class="bi-people p-2" style="font-size: 24px"></i>
      </div>
      <h3 class="fs-2">Фунгициды</h3>
      <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
      <a href="#" class="icon-link d-inline-flex align-items-center">
        Call to action
        <svg class="bi" width="1em" height="1em"><use xlink:href="#chevron-right"></use></svg>
      </a>
    </div>
  </div>
</template>