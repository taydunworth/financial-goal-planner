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

    <div id="sidebar">
      <span id="date">Friday, March 22, 2019</span>
      <ul>
        <li><i class="fas fa-plus"></i> Add Goal</li>
        <li><i class="far fa-credit-card"></i> Integrate with Bank</li>
        <li><i class="fas fa-chart-bar"></i> Track Progress</li>
        <li><i class="fas fa-piggy-bank"></i>Savings Analysis</li>
      </ul>
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

#sidebar {
  background-color: #1F2838;
  width: 22%;
  height: calc(100vh - 70px);
  color: #8f949c;
  padding: 20px;
}

#sidebar ul {
  list-style: none;
  padding: 0;
  margin-top: 50px;
}

#sidebar ul li {
  padding-bottom: 20px;
  margin-bottom: 20px;
  border-bottom: 1px solid #414956;
  transition: .3s color ease-in-out;
}

#sidebar ul li:last-of-type {
  border-bottom: none;
}

#sidebar ul li:hover {
  color: #fff;
  cursor: pointer;
}

#sidebar .fas, #sidebar .far {
  padding-right: 10px;
}

#date {
  text-transform: uppercase;
  font-weight: 700;
  letter-spacing: 1px;
  font-size: .8em;
}

</style>
