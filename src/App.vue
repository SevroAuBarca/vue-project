<script setup>
import Componente1 from "./components/Componente1.vue";
import Componente2 from "./components/Componente2.vue";
import Componente3 from "./components/Componente3.vue";
</script>

<template>
  <div class="container">
    <h1>Mi Practica Vue</h1>
    <Componente1 />
    <Componente2 />
    <Componente3 />
  </div>
</template>

<style scoped>
.container {
  width: 100%;
  display: flex;
  gap: 2rem;
  flex-direction: column;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
</style>
