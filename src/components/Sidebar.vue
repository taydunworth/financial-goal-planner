<template>
  <div id="sidebar">
    <span id="date">Friday, March 22, 2019</span>
    <ul>
      <li><i class="fas fa-plus"></i> Add Goal</li>
      <li><i class="far fa-credit-card"></i> Integrate with Bank</li>
      <li><i class="fas fa-chart-bar"></i> Track Progress</li>
      <li><i class="fas fa-piggy-bank"></i>Savings Analysis</li>
      <li><i class="far fa-arrow-alt-circle-left"></i> Sign Out</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Sidebar'
}
</script>

<style scoped>
#sidebar {
  background-color: #1F2838;
  width: 275px;
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