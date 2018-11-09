<template>
  <div>
    <header>
      <div class="branding">
        <img class ="logo-small" src="./img/fidget-spinner.svg" />
        <span>Nagevación superior</span>
      </div>
      <nav>
        <a href="#/">Home</a>
        <a href="#/actors">Lista</a>
         <a href="#/add">Añadir</a> <!-- Se añade un nuevo link a la pestaña de ingreso a un actor -->
      </nav>
    </header>

    <main class="container">
      <router-view></router-view>
    </main>
    <footer>
      Footer
    </footer>
</div>
</template>

<script>
export default {

}
</script>
