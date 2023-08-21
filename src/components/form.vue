<script>
import card from '../components/card.vue'

export default{
	components:{
		card
	},
	data(){
		return{
			text: ""
		}
	}
}
</script>
<template>
    <div id="form" class="text-white my-3">
      <input v-model="text" placeholder="Agregar texto" class="form-control" type="text">
      <button type="submit" class="btn btn-success w-100 mt-3">Agregar</button>
    </div>
    <card :text="text"/>
</template>