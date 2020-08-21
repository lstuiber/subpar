<template>
  <div class="home">
    Test
    <div class="bg">
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src


export default {
    name: 'Home'

  
}
</script>

<style scoped>
  img {
    width: 70%;
    height: 75vh;
  }
   .bg, .bg2{
    background-image: url("../assets/subpar.png");
      min-height: 35vh;
      max-width: 30%;

    /* Center and scale the image nicely */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>
