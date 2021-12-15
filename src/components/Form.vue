<template>
    <form action="">
        <InputText/>
        <InputText/>
        <SubmitButton/>
    </form>
</template>

<script>
import InputText from './form/InputText.vue'
import SubmitButton from './form/SubmitButton.vue'
export default {
    name:'Form',
    components: {
        InputText,
        SubmitButton
    }
}
</script>