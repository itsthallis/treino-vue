<template>
	<div id="blocos" class="blocos">
		<div class="columns">
			<div class="column is-third flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero praesentium, ab, quibusdam asperiores accusantium facilis! Voluptatum praesentium error tempore ipsum, reprehenderit, non commodi quisquam tenetur natus voluptatibus culpa ex laboriosam. lorem</div>
				<a class="button is-primary is-outlined">Primary</a>
			</div>

			<div class="column is-third flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem harum adipisci accusamus, magni cumque minima, culpa aliquid quo quidem porro aliquam at maiores voluptates consectetur amet possimus eius quod non.</div>
				<a class="button is-primary is-outlined">Primary</a>
			</div>

			<div class="column is-third flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam numquam, nemo accusantium quas? Eum incidunt nisi, aut fuga officiis dolore magni perspiciatis dicta! Eaque nostrum a quas aspernatur explicabo alias. lorem</div>
				<a class="button is-primary is-outlined">Primary</a>
			</div>
		</div>
	</div>
</template>

<script>

	export default {
	  name: 'blocos',
	  data: {
	    
	  }
	}
</script>

<style scoped>
	.column{
		background-color: #eee;
		min-height: 30vh
	}
	.flexd{
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
	a{
		margin-top: 2vh;
	}
	.texto{
		min-height: 121px;
	}
</style>