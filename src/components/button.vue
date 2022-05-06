<template>
    <button :style="{ background: color }"> {{ text }}</button>
</template>



<script>
    export default {
        name:'Button',
        props: {
            text:String,
            color:String,
        },
    }
</script>


<style>
button{
    background-color: brown;
    color: white;
    padding: 10px;
    border: none;
    height: 30px;
    width: 50px;

}
</style>