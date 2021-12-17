<template>
  <div class="container" style="text-align: -webkit-center;">
    <info/>  
  </div>
  
</template>

<script>
import Info from './components/Info.vue'
import Form from './components/Form.vue'
import LifeCycle from './components/LifeCycle.vue'
import primeiroComponente from './components/primeiroComponente.vue'

export default {
  name: 'App',
  components:{
    Info,
    Form,
    LifeCycle,
    primeiroComponente
  }
    
}
</script>

<style>
  body{
    background-color: aqua;
    color: blueviolet;
    text-align: center;
    margin-top: 20rem;
  }
  

</style>