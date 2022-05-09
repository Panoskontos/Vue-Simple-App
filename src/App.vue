
<!-- HTML -->
<template>
  <div class="container">
    <Header title="Task Tracker" />

    <Tasks :tasks="tasks"/>

</div>
</template>



<!-- Script -->
<script>
// Import component
import Header from './components/header.vue'
import Tasks from './components/Tasks.vue'

// Register Component to embedd it
export default {
  name: 'App',
  components: {
    Header, Tasks
},
data(){
  // return empty array
  return {
    tasks: []
  }
},

// When created runs we fill the array
created(){
  // array of objects
  this.tasks = [
    {
      id:1,
      text:"Doctors",
      date:"Monday",
      reminder:true,
    },
    {
      id:2,
      text:"Lawyers",
      date:"Tuesday",
      reminder:true,
    },
  ]
}
}
</script>




<!-- CSS -->
<style>
* {
  margin: 0;
  padding: 0;
}
body {
  background-color: aliceblue;
}
</style>
