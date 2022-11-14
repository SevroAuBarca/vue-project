<script></script>

<template>
  <h2>Instalacion de proyecto</h2>

  <ul>
    <li>
      Revisar si node.js esta instalado:
      <div class="code">
        <code>node --version</code>
        <code> v16.17.1 </code>
      </div>
    </li>
    <li>
      Instalar de forma global el CLI de vue.js
      <div class="code">
        <code>npm i -g vue@cli</code>
      </div>
    </li>
    <li>
      Puede usar Vite para instalarlo
      <div class="code">
        <code>npm create vite@latest</code>
      </div>
    </li>
    <li>
      Ir a la carpeta
      <div class="code">
        <code>cd 'Mi carpeta' </code>
      </div>
    </li>
    <li>
      Usar npm run serve o npm run dev
      <div class="code">
        <code>npm serve </code>
        <code>npm run dev </code>
      </div>
    </li>
  </ul>
</template>

<style>
ul {
  list-style: none;
}
li div {
  margin-top: 10px;
  padding: 1rem;
  background-color: hsla(160, 89%, 42%, 0.2);
  border-radius: 12px;
}
.code {
  display: flex;
  flex-direction: column;
  gap: 5px;
}
</style>
