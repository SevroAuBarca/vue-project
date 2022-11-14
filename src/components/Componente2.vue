<template>
  <h2>Estructura del proyecto</h2>

  <ul>
    <li class="folder">vscode</li>
    <li class="folder">node_modules</li>
    <li class="folder">public</li>
    <li class="folder">
      src
      <ul>
        <li class="folder">assets</li>
        <li class="folder">components</li>
        <li class="folder">store</li>
        <li>app.vue</li>
        <li>main.js</li>
      </ul>
    </li>
    <li></li>
  </ul>
</template>

<script></script>

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
.folder::before {
  content: url("https://api.iconify.design/vscode-icons:folder-type-app.svg");
  margin-right: 1rem;
}
li ul {
  margin-left: 2rem;
}
</style>
