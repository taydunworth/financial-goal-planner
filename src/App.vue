<template>
  <div id="app">
    <app-header></app-header>
    <div class="wrapper">
      <app-sidebar></app-sidebar>
      <div id="body">
        <div id="intro">
          <h1>Praesent scelerisque, nunc a pharetra</h1>
          <p>Mauris vel porttitor tellus. Donec non libero feugiat, sollicitudin nunc quis, tincidunt diam. Vivamus in est at justo euismod egestas. Duis convallis et quam ac interdum.</p>
        </div>
        <app-tip></app-tip>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
import Tip from "./components/Tip.vue";

export default {
  name: 'app',
  components: {
    appHeader: Header,
    appSidebar: Sidebar,
    appTip: Tip
  },
}
</script>

<style>
body {
  font-family: 'Noto Sans JP', sans-serif;
  background: linear-gradient(rgba(22,33,46,.95), rgba(22,33,46,.95)), url('./assets/texture.jpeg');
  background-size: cover;
  height: 100vh;
  font-size: 16px;
}

h1 {
  font-size: 1.5em;
}

p {
  font-size: .8em;
  line-height: 1.5em;
}

.wrapper {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

#body {
  padding: 20px;
  width: calc(100% - 275px);
}

#intro {
  width: 100%;
  color: #fff;
}
</style>
