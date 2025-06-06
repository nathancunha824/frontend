<template>
  <div class="d-flex align-items-center gap-3 px-3 py-2 w-100" id="menuPrincipal">
    <!-- Botão -->
    <button class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasWithBothOptions" aria-controls="offcanvasWithBothOptions">
      <i class="bi bi-list"></i>
    </button>

    <!-- Título -->
    <div id="title">
      <h1 class="fs-4 m-0">Agenda de contatos</h1>
    </div>

    <!-- Pesquisa -->
    <div class="search d-flex align-items-center">
      <i class="bi bi-search" id="iconSearch"></i>
      <input type="search" id="searchBar" placeholder="Pesquisar..">
    </div>

    <!-- Icons perfil/settings no canto direito -->
    <div class="d-flex align-items-center gap-3 ms-auto" id="iconsHeader">
      <i class="bi bi-person-circle" id="iconPerfil"></i>
      <i class="bi bi-gear" id="iconSettings"></i>
    </div>
  </div>

  <!-- Offcanvas -->
  <div class="offcanvas offcanvas-start" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
    <div class="offcanvas-header">
      <h1 class="offcanvas-title" id="offcanvasWithBothOptionsLabel">Painel</h1>
      <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
    </div>
    <div class="offcanvas-body">
      <h3>Contatos</h3>
      <h3>Contatos frequentes</h3>
      <h3>Configurações</h3>
    </div>
  </div>  
</template>

<style scoped>
  #menuPrincipal {
    background-color: #000080;
    font-family: "Ancizar Sans", sans-serif;
  }
  #title h1{
    color: white;
    font-family: "Ancizar Sans", sans-serif;
  }
  button {
    font-size: 25px;
    color: white;
    font-family: "Ancizar Sans", sans-serif;
  }
  .offcanvas-body {
    background-color: #f6f3f3;
  }
  #searchBar {
    border-radius: 12px;
    width: 332px;
    margin-left: 15px;
  }
  #iconSearch {
    color: white;
    margin-left: 45px;
  }

  #iconsHeader, #iconPerfil i{
    color: white;
    font-size: 22px;
    cursor: pointer;
  }
</style>
