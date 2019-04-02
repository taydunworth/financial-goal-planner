<template>
    <div id="stock-insight">
        <h2>Stock Sector Overview</h2>
        <div class="sector" id="healthcare">
            <span class="sector-head">Healthcare</span>
            <span class="sector-number">-0.03%</span>
        </div>
        <div class="sector" id="technology">
            <span class="sector-head">Technology</span>
            <span class="sector-number">+1.15%</span>
        </div>
        <div class="sector" id="real-estate">
            <span class="sector-head">Real Estate</span>
            <span class="sector-number">+2.04%</span>
        </div>
        <div class="sector" id="energy">
            <span class="sector-head">Energy</span>
            <span class="sector-number">-0.89%</span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'StockInsight'
}
</script>

<style scoped>
#stock-insight {
    background-color: #1F2838;
    border-radius: 10px;
    padding: 15px;
    color: #fff;
    min-height: 50vh;
}

#stock-insight h2 {
    padding-bottom: 10px;
}

.sector {
    height: 60px;
    width: 100%;
    background-color: #405876;
    display: flex;
    justify-content: space-between;
    align-content: flex-end;
    margin: 10px 0;
    padding: 10px;
    font-size: .8em;
}

.sector:last-of-type {
    margin-bottom: 0;
}

.sector-head {
    color: #fff;
    text-transform: uppercase;
    font-weight: 600;
    display: block;
    width: 100%;
}

.sector-number {
    color: #fff;
    text-transform: uppercase;
    font-weight: 600;
    display: inline-block;
    text-align: center;
    width: 70px;
    background-color: rgba(0, 0, 0, .5);
    border-radius: 10px;
    padding: 3px;
    margin-top: 15px;
}
</style>