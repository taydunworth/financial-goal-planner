<template>
  <div id="app">
    <app-header></app-header>
    <app-sidebar></app-sidebar>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";

export default {
  name: 'app',
  components: {
    appHeader: Header,
    appSidebar: Sidebar
  },
}
</script>

<style>
body {
  font-family: 'Noto Sans JP', sans-serif;
  background: linear-gradient(rgba(22,33,46,.95), rgba(22,33,46,.95)),
    url('./assets/texture.jpeg');
  background-size: cover;
  height: 100vh;
  font-size: 16px;
}
</style>
