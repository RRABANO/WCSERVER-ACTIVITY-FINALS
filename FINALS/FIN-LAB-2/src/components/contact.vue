<template>
    <div class="contact">
      <h1>Welcome to HIP-HOP World</h1>
      <img src="https://scontent.fcrk1-5.fna.fbcdn.net/v/t39.30808-6/315166188_1347766825976574_1516302386044816842_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=09cbfe&_nc_eui2=AeHl6zxUPDYUDuj_yI33CsV8OBTq613hwl84FOrrXeHCX-0RC12kyHbZ8aaiDA46s5X-fGqgnuIzJbIbooKHLXY9&_nc_ohc=WntnWAUx4U0AX-R7CNi&_nc_ht=scontent.fcrk1-5.fna&oh=00_AfBAgZEeV7BjlDRrZEMG9axK1h95ATKz4RtG0Arql8VIvA&oe=64495B78" >
      <h2>
        Name: Rymbrent Maximillian L. Rabano <br>
        Contact Number: 09685800111 <br>
        Email: rymbrent@gmail.com <br>
        Facebook: Rymbrent Rabano <br>
      </h2>
    </div>
  </template>
  
  <script>
  export default {
    name: 'contact',
    data () {
      return {
        title: 'Contact'
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
    width: 600px;
  }
  h2{
    font-family: 'Courier New', Courier, monospace;
    font-size: 25px;
    color: white;
    text-align: left;
    padding: 3%;
  }
</style>