<template>
  <header>Todo list technical testing</header>

  <hr />

  <slot />

  <hr />

  <footer>Vue 3</footer>
</template>

<script setup lang="ts"></script>

<style lang="scss">
header,
footer {
  text-align: center;
  font-weight: bold;
}
</style>
