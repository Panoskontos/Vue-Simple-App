<template>
<div class="task">
    <h3>{{task.text}}</h3>
    <br>
    <i class="bi bi-x-circle"></i>
    <br>
    <p>{{task.date}}</p>
</div>
</template>

<script>
export default {
    name:"Task",
    props: {
        task:Object
    },
    

}

</script>

<style scoped>
    .task{
        background-color: rgb(218, 244, 244);
        border: 1px solid black;
        border-radius: 10px;
        padding: 20px;
        width: 300px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;

    }

    i {
        background-color: red;
        color: white;
        padding: 2px;
    }
</style>