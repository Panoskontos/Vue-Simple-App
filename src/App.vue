
<!-- HTML -->
<template>
  <div class="container">
    <Header title="Task Tracker" />
  </div>
</template>



<!-- Script -->
<script>
// Import component
import Header from './components/header.vue'

// Register Component to embedd it
export default {
  name: 'App',
  components: {
    Header,
},
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
