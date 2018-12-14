<template>
	<div id="titulo" class="titulo">
		<p>{{title}}</p>
	</div>
</template>

<script>
	export default {
	  name: 'titulo',
	  el: '#titulo',
	  data() {
	  	return{
		  	title: 'olá mundo'
	  	}
	  }
	}
</script>

<style scoped>
	p{
		font-size: 75px;
		color: #101010;
		font-weight: bold;
		text-transform:uppercase;
	}
</style>