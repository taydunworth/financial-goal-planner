<template>
    <div id="financial-tip">
        <h2>Financial Saving Tip</h2>
        <p>{{finTips[Math.floor(Math.random() * finTips.length)]}}</p>
    </div>
</template>

<script>
import { FinTips } from "../data/fintips";

export default {
    components: {
        name: 'Tip'
    },
    data() {
      return {
        finTips: FinTips
      };
    }
}
</script>

<style scoped>
#financial-tip {
    background-color: #1F2838;
    border-radius: 10px;
    padding: 15px;
    color: #fff;
}

#financial-tip p {
    padding-top: 10px;
    margin-bottom: 0;
}
</style>