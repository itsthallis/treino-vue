<template>
	<div>
		<div class="modal" v-bind:class="{ active: modalactive }">
		  <div class="modal-background"></div>
		  <div class="modal-card">
		    <header class="modal-card-head">
		      <p class="modal-card-title">Modal title</p>
		      <button class="delete" v-on:click="modalactive = !modalactive" aria-label="close"></button>
		    </header>
		    <section class="modal-card-body has-text-left">
		      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt mollitia, sapiente nostrum dolor aperiam fugiat rem excepturi beatae harum ea possimus. At atque quidem alias necessitatibus qui, nobis magni accusamus.
		    </section>
		    <footer class="modal-card-foot">
		      <button class="button is-success">Save changes</button>
		      <button class="button" v-on:click="modalactive = !modalactive">Cancel</button>
		    </footer>
		  </div>
		</div>

		<div class="columns">
			<div class="column flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero praesentium, ab, quibusdam asperiores accusantium facilis! Voluptatum praesentium error tempore ipsum, reprehenderit, non commodi quisquam tenetur natus voluptatibus culpa ex laboriosam. lorem</div>
				<button v-on:click="modalactive = !modalactive" class="button is-primary is-outlined">Modal</button>
			</div>
			<div class="column flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero praesentium, ab, quibusdam asperiores accusantium facilis! Voluptatum praesentium error tempore ipsum, reprehenderit, non commodi quisquam tenetur natus voluptatibus culpa ex laboriosam. lorem</div>
				<button v-on:click="modalactive = !modalactive" class="button is-primary is-outlined">Modal</button>
			</div>
			<div class="column flexd">
				<div class="texto">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Libero praesentium, ab, quibusdam asperiores accusantium facilis! Voluptatum praesentium error tempore ipsum, reprehenderit, non commodi quisquam tenetur natus voluptatibus culpa ex laboriosam. lorem</div>
				<button v-on:click="modalactive = !modalactive" class="button is-primary is-outlined">Modal</button>
			</div>
		</div>
	</div>
</template>

<script>

	export default {
	  name: 'blocos',
	  data(){
	    return{
	    	modalactive: false
	    }
	  }
	}
</script>

<style scoped>
	.active{
		display: inline-block;
	}
	.column{
		background-color: #eee;
		min-height: 30vh;
		border-radius: 15px;
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
</style>