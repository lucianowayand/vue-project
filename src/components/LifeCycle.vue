<template>
    <h1>My name is: {{name}}</h1>
</template>

<script>
export default {
    name: 'LyfeCycle',
    data(){
        return{
            name:'WIP'
        }
    },
    created(){
        setTimeout(()=>{
            this.name = "Name"
        }, 1000)
        
    }
}
</script>