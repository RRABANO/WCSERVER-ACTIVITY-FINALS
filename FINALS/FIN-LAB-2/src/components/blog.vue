<template>
    <div class="blog">
      <h1>Welcome to HIP-HOP World</h1><br>
      <div class="container">
            <h1>This is Top 6 best Hip-Hop Albums Cover</h1>
            <img src="https://townsquare.media/site/812/files/2020/05/Illustrated-album-covers.jpg?w=1200" >
            <p>
              Top 1 - Kid Cudi, Man on the Moon: The End of Day (2009) <br>
              Top 2 - Drake, Nothing Was the Same (2013) <br>
              Top 3 - Lil Uzi Vert, Lil Uzi Vert vs. The World (2016) <br>
              Top 4 - Chance The Rapper, Acid Rap (2013) <br>
              Top 5 - Cole, KOD (2018) <br>
              Top 6 - Kanye West, Graduation (2007) <br>
            </p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'blog',
    data () {
      return {
        title: 'Blog'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .blog{
  font-family: 'Courier New', Courier, monospace;
  font-size: 50px;
  color: white;
  }
  img{
    width: 1000px;
  }
  h2{
    font-family: 'Courier New', Courier, monospace;
    font-size: 15px;
    color: white;
    text-align: center;
    padding: 3%;
  }
  p{
    font-family: 'Courier New', Courier, monospace;
    font-size: 20px;
    color: white;
    text-align: center;
    padding: 3%;
  }
  </style>