<template>
	<div>
		<h1>Cadastrar os Pokemons</h1>
		  <form @submit.prevent="addPost">
		   	<div class="row">
		   	 	<div class="cols-md-6">
		   	 	 	<div class="form-group">
		   	 	 		<label>Nome do Pokemon</label>
		   	 	 		<textarea class="form-control" v-model="post.body" rows="5"></textarea>
		   	 	 	</div>
		   	 	</div>
		   	</div></br>
		   		<div class="form-group">
		   			<button class="btn btn-primary">Cadastrar</button>
		   		</div>
		  </form>
	</div>
</template>

<script>
	export default {
		data(){
		return{
		 post:{}
		}
	},

	methods: {
		addPost(){
			console.log(this.post);
			}
		}
	}
</script>