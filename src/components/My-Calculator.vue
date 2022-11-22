<template>
  <div class="calculator">
    <div class="display">0.234234</div>
    <div class="btns reset-btn">C</div>
    <div class="btns operation-btns">+/-</div>
    <div class="btns operation-btns">%</div>
    <div class="btns operation-btns">/</div>
    <div class="btns">7</div>
    <div class="btns">8</div>
    <div class="btns">9</div>
    <div class="btns operation-btns">X</div>
    <div class="btns">4</div>
    <div class="btns">5</div>
    <div class="btns">6</div>
    <div class="btns operation-btns">-</div>
    <div class="btns">1</div>
    <div class="btns">2</div>
    <div class="btns">3</div>
    <div class="btns operation-btns">+</div>
    <div class="btns zero">0</div>
    <div class="btns operation-btns">.</div>
    <div class="btns equal-btn">=</div>
  </div>
</template>

<script>
export default {
  name: 'MyCalculator'
}
</script>


<style scoped>
  .calculator{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-auto-rows: minmax(50px, auto);
    font-size: 35px;
    padding: 20px;
  }

  .display{
    grid-column: 1 / 5;
    background-color: #E5E5E5;
    height: 130px;
    margin-bottom: 30px;
    border-radius: 20px;
    padding: 20px;
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
    box-shadow: 2px 4px 5px #B6B6B6;
  }

  .zero{
    grid-column: 1 / 3;
  }

  .btns{
    margin: 10px;
    border-radius: 10%;
    box-shadow: 2px 4px 5px #B6B6B6;
    background-color: #3F4556;
    color: #FFFFFF;
    cursor: pointer;
    transition: all .2s;
  }

  .btns:hover{
    transform: scale(1.02);
  }

  .operation-btns{
    color: #FF806E;
  }

  .reset-btn{
    background-color: #FF806E;
  }

  .equal-btn{
    background-color: #FF806E;
  }
</style>
