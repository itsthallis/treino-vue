<template>
	<div class="imagemetexto">
		<div class="columns">
			<div class="column is-half flexd"><font-awesome-icon icon="coffee" class="fa-10x"/></div>
			<div class="column is-half flexd">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima iure voluptas facilis excepturi expedita fugit, quisquam dolorum molestias itaque vero earum suscipit, pariatur animi fuga consequuntur, dolores totam veritatis aut!</div>
		</div>
	</div>
</template>

<script>
	export default {

	  name: 'imagemetexto',

	  	data: {
	  		
		}
	  }
</script>

<style scoped>
	.imagemetexto {
	  margin-top: 5vh;
	}

	.flexd{
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}

	.column{
		min-height: 50vh;
	}
</style>