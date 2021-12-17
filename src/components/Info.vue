<template>
    <div class="box">
        <p>Password is: {{password}}</p>
        <button @click="showPassword">{{buttonText}}</button>
    </div>
    <div class="box" style="margin-top:2rem; text-align:left;">
        <ul>
            <li v-for="(lang, index) in list" v-bind:key="index">{{lang}}</li>
        </ul>
    </div>
    
</template>

<script>
export default {
    name:'Info',
    data(){
        return{
            password: "*****",
            buttonText: "Show password",
            list: ['Ruby', 'Python', 'Vue', 'Javascript', 'C']
            //You can even pass dicts and refer to it by dict.key
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
    padding: 3rem;
    width: fit-content;
  }
</style>

