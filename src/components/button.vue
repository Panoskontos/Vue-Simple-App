<template>
    <button @click="onClick()" :style="{ background: color }"> {{ text }}</button>
</template>



<script>
    export default {
        name:'Button',
        props: {
            text:String,
            color:String,
        },
        methods: {
            onClick(){
                console.log('click')
            }
        }
    }
</script>


<style>
button{
    background-color: brown;
    color: white;
    border:none;
    border-radius: 10px;
    padding: 10px;
    width: 80px;
   

}
</style>