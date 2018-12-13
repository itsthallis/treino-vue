<template>
	<div class="parallax">
		
	</div>
</template>

<script>
	export default {

	  name: 'parallax',

	  	data: {
	  		
		}
	  }
</script>

<style scoped>
	.parallax {
	  /* The image used */
	  background-image: url("../assets/Wallpaper-4K.jpg");

	  /* Set a specific height */
	  height: 500px;

	  /* Create the parallax scrolling effect */
	  background-attachment: fixed;
	  background-position: center;
	  background-repeat: no-repeat;
	  background-size: cover;

	  margin-top: 5vh;
	}
</style>