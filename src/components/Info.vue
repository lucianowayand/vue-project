<template>
    <p>Password is: {{password}}</p>
    <button @click="showPassword">{{buttonText}}</button>
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

