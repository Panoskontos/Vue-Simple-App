<!-- create your code inside your components -->

<template>
    <header>
        <h1> {{ title }} </h1>
        <br>
        <Button color="blue" text="Add" />
       
    </header>
</template>

<script>
import Button from './button.vue'



    export default {
        name:'Header',
        props: {
            title: String,
        },
        components: {
    Button,
},
    }
</script>

<style>
header{
    margin-top: 40px;
    margin-left: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 600px;
    height: 300px;
    background-color: white;
    border: 1px solid blanchedalmond;
}
</style>