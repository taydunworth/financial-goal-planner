<template>
  <div id="app">
    <app-header></app-header>
    <div class="wrapper">
      <app-sidebar></app-sidebar>
      <div class="content-body">
        <div class="intro">
          <h1>Praesent scelerisque, nunc a pharetra</h1>
          <p>Mauris vel porttitor tellus. Donec non libero feugiat, sollicitudin nunc quis, tincidunt diam. Vivamus in est at justo euismod egestas. Duis convallis et quam ac interdum.</p>
        </div>
        <div class="content-inner-body">
          <div class="left-side">
            <app-goal-list></app-goal-list>
          </div>
          <div class="right-side">
            <app-stock-insight></app-stock-insight>
            <app-tip></app-tip>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
import GoalList from "./components/GoalList.vue";
import StockInsight from "./components/StockInsight.vue";
import Tip from "./components/Tip.vue";

export default {
  name: 'app',
  components: {
    appHeader: Header,
    appSidebar: Sidebar,
    appGoalList: GoalList,
    appStockInsight: StockInsight,
    appTip: Tip
  },
}
</script>

<style>
body {
  font-family: 'Noto Sans JP', sans-serif;
  background: linear-gradient(rgba(22,33,46,.9), rgba(22,33,46,.9)), url('./assets/texture.jpeg');
  background-size: cover;
  height: 100vh;
  font-size: 16px;
}

h1 {
  font-size: 1.5em;
}

h2 {
  font-size: 1em;
}

p, li {
  font-size: .8em;
  line-height: 1.5em;
}

.wrapper {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.content-body {
  padding: 20px;
  width: calc(100% - 275px);
}

.intro {
  width: 100%;
  color: #fff;
}

.content-inner-body {
  display: flex;
  justify-content: space-between;
}

.left-side {
  width: calc(65% - 20px);
}

.right-side {
  width: 35%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
