<template>
  <div class="blog">
    <div class="container">
		  <div class="gallery">
			  <img src="https://static.onecms.io/wp-content/uploads/sites/6/2020/06/09/Best-Albums-of-the-year3.jpg">
			  <img src="https://media.gq-magazine.co.uk/photos/63341fa5885571856e6edb7d/16:9/pass/Best-pop-albums-of-the-21st-century-hp-b.jpg">
			  <img src="https://hips.hearstapps.com/hmg-prod/images/best-albums-2018-1536595480.jpg">
			  <img src="https://townsquare.media/site/812/files/2019/10/Kanye-West-OutKast-Tyler-The-Creator-Eminem-Lil-Wayne-50-Cent.jpg?w=980&q=75">
			  <img src="https://www.rollingstone.com/wp-content/uploads/2019/12/RS-BestAlbumofDecade.jpg">
		  </div>
	  </div>
  </div>
</template>
  
  <script>
  export default {
    name: 'gallery',
    data () {
      return {
        title: 'Gallery'
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 1000px;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}
.container {
	width: 90%;
	margin: 0 auto;
}

.gallery {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	align-items: center;
}

img {
	width: 1000px;
	height: 250px;
	margin: 10px;
	object-fit: cover;
	cursor: pointer;
}

img:hover {
	opacity: 0.7;
}
  </style>