<template>
	<div>
		<p class="subtitulo" v-bind:class="{ hidden: xazam }">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae error nesciunt mollitia corrupti alias quos excepturi repudiandae fugit facilis maiores molestias quam eius, numquam necessitatibus expedita quae, animi deserunt totam!</p>
		<button v-on:click="xazam = true" class="button is-primary is-large">clique aqui</button>
	</div>
</template>

<script>
	export default {

	  name: 'subtitulo',

	  	data: {
	  		xazam: true
		}
	  }
</script>

<style scoped>
	p{
		font-size: 30px !important;
	}
	button{
		margin-top: 2vh
	}
	.hidden{
		display: none;
	}
</style>