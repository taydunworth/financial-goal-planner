<template>
    <div id="goal-list">
        <ul>
            <li>
                <i class="fas fa-hand-holding-usd"></i>
                <div class="goal-text">
                    <h3>Goal title vel porttitor tellus donec non</h3>
                    <p>Description sollicitudin nunc quis, tincidunt diam. Vivamus in est at justo euismod egestas. Duis convallis
    et quam ac interdum.</p>
                    <p class="goal-number"><span>$100.34</span> saved of <span>$123,456.00</span></p>
                </div>
                <div class="utility-icons">
                    <i class="fas fa-pencil-alt"></i>
                    <i class="far fa-times-circle"></i>
                </div>
            </li>
             <li>
                <i class="fas fa-hand-holding-usd"></i>
                <div class="goal-text">
                    <h3>Goal title vel porttitor tellus donec non</h3>
                    <p>Description sollicitudin nunc quis, tincidunt diam. Vivamus in est at justo euismod egestas. Duis convallis
    et quam ac interdum.</p>
                    <p class="goal-number"><span>$100.34</span> saved of <span>$123,456.00</span></p>
                </div>
                <div class="utility-icons">
                    <i class="fas fa-pencil-alt"></i>
                    <i class="far fa-times-circle"></i>
                </div>
            </li>
             <li>
                <i class="fas fa-hand-holding-usd"></i>
                <div class="goal-text">
                    <h3>Goal title vel porttitor tellus donec non</h3>
                    <p>Description sollicitudin nunc quis, tincidunt diam. Vivamus in est at justo euismod egestas. Duis convallis
    et quam ac interdum.</p>
                    <p class="goal-number"><span>$100.34</span> saved of <span>$123,456.00</span></p>
                </div>
                <div class="utility-icons">
                    <i class="fas fa-pencil-alt"></i>
                    <i class="far fa-times-circle"></i>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'GoalList'
}
</script>

<style scoped>
#goal-list {
    background-color: #1F2838;
    border-radius: 10px;
    padding: 15px;
    color: #fff;
    min-height: 70vh;
}

#goal-list p {
    padding-top: 10px;
    margin-bottom: 0;
}

#goal-list ul {
    list-style: none;
    padding: 0;
}

#goal-list ul li {
    display: flex;
    justify-content: space-between;
    width: 100%;
    border-bottom: 1px solid #414956;
    padding: 20px 0;
}

#goal-list ul li:nth-of-type(1) {
    padding-top: 0;
}

.fa-hand-holding-usd {
    font-size: 2em;
    color: #9AB73F;
    padding-right: 20px;
    width: 5%;
}

.goal-text {
    width: 85%;
}

.utility-icons {
    display: flex;
    width: 5%;
    justify-content: space-between;
    font-size: 1.1em;
    color: #8f949c;
}

.goal-number {
    font-size: 1.2em;
    font-weight: 300;
}

.goal-number span {
    color: #9AB73F;
    font-weight: 700;
}
</style>