<template>
  <div class="d-flex align-items-center gap-3 px-3 py-2" id = "menuPrincipal">
    <!-- Botão -->
    <button class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasWithBothOptions" aria-controls="offcanvasWithBothOptions">
      <i class="bi bi-list"></i>
    </button>

    <!-- Título à direita -->
    <div id="title">
      <h1 class="fs-4 m-0">Agenda de contatos</h1>
    </div>
  </div>

  <!-- Offcanvas -->
  <div class="offcanvas offcanvas-start" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
    <div class="offcanvas-header">
      <h5 class="offcanvas-title" id="offcanvasWithBothOptionsLabel">Backdrop with scrolling</h5>
      <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
    </div>
    <div class="offcanvas-body">
      <p>Try scrolling the rest of the page to see this option in action.</p>
    </div>
  </div>
</template>

<style scoped>
    #menuPrincipal {
        background-color: #000080;
    }
    #title h1{
        color: white;
        font-family: "Ancizar Sans", sans-serif;
    }
    button {
        font-size: 25px;
        color: white;
    }
</style>
