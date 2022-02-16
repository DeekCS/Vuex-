<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
      <Counter />
      <Square />
      <Button />
      <InputColor/>
  </div>
</template>

<script>
import Counter from '../components/Counter.vue'
import Square from '../components/Square.vue'
import Button from '../components/Button.vue'
import InputColor from '../components/InputColor.vue'
export default {
  name: 'Home',
  components:{
    Counter,
    Square,
    Button,
    InputColor
  },
  
}
</script>

<style >
  div {
    margin-bottom: 10px;
  }

  .counter {
    font-size: 80px;
  }
  .button button {
    font-size: 40px;
    width: 100px;
    margin: 0 10px ;
  }
</style>