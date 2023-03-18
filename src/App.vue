<template>
  <div class="app">
    <Calculator></Calculator>
  </div>
  <router-view />
</template>

<script>
import Calculator from './components/Calculator.vue';
export default{
  name:'app',
  components:{
    Calculator
  }
}
</script>


