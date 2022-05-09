<template>
    <div v-for="task in tasks">
        <Task :task="task"/>
    </div>
</template>



<script>
import Task from './Task.vue'




    export default {
        name:'Tasks',
        // here we will add our data
        props: {
            tasks:Array
        },
        components: {
    Task
},
    }
</script>


<style>

</style>