<template>
  <div style="text-align: -webkit-center;">
    <Prop imageLink="https://spemer.com/img/works/vue/thumb.png" imageAlt="Vue logo"/>
    <info/>  
  </div>
  
</template>

<script>
import Prop from './components/Prop.vue'
import Info from './components/Info.vue'
import Form from './components/Form.vue'
import LifeCycle from './components/LifeCycle.vue'
import primeiroComponente from './components/primeiroComponente.vue'

export default {
  name: 'App',
  components:{
    Prop,
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
  }
  

</style>