<template>
  <Info/>
</template>

<script>
import Info from './components/Info.vue'
export default {
  name: 'App',
  components:{
    Info
  }
    
}
</script>

<style>
  body{
    background-color: aqua;
    color: blueviolet;

    margin-top:25rem;
  }
  .box{
    background-color: red;
    max-width: fit-content;
    text-align: center;
    padding: 3rem;
  }
</style>