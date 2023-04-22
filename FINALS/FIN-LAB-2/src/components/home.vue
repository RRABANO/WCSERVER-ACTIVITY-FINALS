<template>
  <div class="home">
      <h1>Welcome to HIP-HOP World</h1>
      <img src="https://www.throwup.it/wp-content-throwup/uploads/2019/12/top-25-album-1600x900.jpg" >
      <h2>Welcome to my Hip-hop website.
        this is a website for all of the hip-hop music that you need. you can see newer albums.
        and Song and about the artist. This website is for only music and ablums related. 
      </h2>
    
  </div>

</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  font-family: 'Courier New', Courier, monospace;
  font-size: 50px;
  color: white;
}
img{
  width: 1000px;
}
h2{
  font-family: 'Courier New', Courier, monospace;
  font-size: 25px;
  color: white;
  text-align: center;
  padding: 3%;
}

</style>
