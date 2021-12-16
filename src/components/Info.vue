<template>
    <p v-if="!employed">Im am currently unemployed</p>
    <p v-else>Im am currently employed</p>
</template>

<script>
export default {
    name:'Info',
    data(){
        return{
            employed: false
        }
    }
}
</script>