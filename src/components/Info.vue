<template>
    <div class="box">
        <p>Password is: {{password}}</p>
        <button @click="showPassword">{{buttonText}}</button>
    </div>
    
</template>

<script>
export default {
    name:'Info',
    data(){
        return{
            password: "*****",
            buttonText: "Show password"
        }
    },
    methods:{
        showPassword(){
            if(this.password == "*****"){
                this.password = "Password"
                this.buttonText = "Hide Password"
            }else{
                this.password = "*****"
                this.buttonText = "Show Password"
            }
                
        }
    }
}
</script>

<style>
    .box{
    background-color: white;
    max-width: fit-content;
    padding: 3rem;
  }
</style>

