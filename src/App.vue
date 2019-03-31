<template>
  <div id="app">
    <div id="header">
      <div id="logo">
        <i class="fas fa-search-dollar"></i>
        <h1>money<span>wise</span></h1>
      </div>
      <div id="user-info">
          <img src="https://via.placeholder.com/30">
          <span>Taylor Cox</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
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

#header {
  width: 100%;
  background-color: #232D40;
  box-shadow: 0 3px 30px rgba(0, 0, 0, .35);
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #fff;
}

#logo {
  display: flex;
  align-items: center;
}

#logo h1 {
  color: #fff;
  display: inline;
  font-weight: 400;
  letter-spacing: 1px;
  font-size: 1.5em;
}

#logo span, #logo .fas {
  color: #9AB73F;
}

#logo .fas {
  font-size: 2em;
  padding-right: 10px;
}

#user-info {
  display: flex;
  align-items: center;
}

#user-info img {
  padding-right: 10px;
}

</style>
