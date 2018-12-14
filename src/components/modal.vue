<template>
	<div class="modal">
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
	      <button class="button" v-on:click="chamarPai()">Cancel</button>
	    </footer>
	  </div>
	</div>
</template>

<script>
	export default {
	  name: 'modal',
	  data(){
	    return{
	    	modalactive: false
	    }
	  },
	  methods:{
	  	chamarPai() {
            this.$emit('chamou');
        }
	  }
	}
</script>

<style>
	
	/*.modal{
		display: flex;
		justify-content: center;
		align-items: center;
	}*/
</style>
