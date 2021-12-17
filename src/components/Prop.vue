<template>
    <img v-bind:src="imageLink" v-bind:alt="imageAlt">
</template>

<script>
export default {
    name:'Prop',
    props:{
        imageLink : String,
        imageAlt : String
    }
}
</script>