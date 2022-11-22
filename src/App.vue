<template>
  <MyCalculator/>
</template>

<script>
import MyCalculator from './components/My-Calculator.vue'

export default {
  name: 'App',
  components: {
    MyCalculator
  }
}
</script>

<style>
body{
  background-color: #E5E5E5;
  display: flex;
  justify-content: center;
  align-items: center;
}

@font-face{
  font-family: roboto;
  src: url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
}

#app {
  font-family: roboto;
  font-weight: 900;
  font-size: 72px;
  line-height: 65px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #3F4556;
  margin-top: 20px;
  background-color: #FFFF;
  width: 500px;
  border-radius: 10px;
}
</style>
