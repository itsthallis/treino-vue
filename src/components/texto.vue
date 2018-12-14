<template>
	<div>
		
		<modal v-on:chamou="respondeu"/>

		<div class="columns">
			<div class="column flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero praesentium, ab, quibusdam asperiores accusantium facilis! Voluptatum praesentium error tempore ipsum, reprehenderit, non commodi quisquam tenetur natus voluptatibus culpa ex laboriosam. lorem</div>
				<button v-on:click="modalactive = !modalactive" class="button is-primary is-outlined">Modal</button>
			</div>
		</div>
	</div>
</template>

<script>
import modal from './modal.vue'

	export default {
	  name: 'blocos',
	  components: {
	  	modal
	  },

	  methods:{
	  	respondeu() {
	  		this.modalactive = !modalactive
	  	}
	  },

	  data(){
	    return{
	    	modalactive: false
	    }
	  }
	}
</script>

<style scoped>
	.column{
		background-color: #eee;
		min-height: 30vh;
		border-radius: 15px;
		margin: 1vw;
	}
	.flexd{
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}
	button{
		margin-top: 2vh;
	}
	.texto{
		min-height: 121px;
	}
	.modal.active{
		display: inline-block;
	}
</style>