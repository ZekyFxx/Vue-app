<script>
export default{
  props:['text'],
  data(){
    return{

    }
  }
}
</script>
<template>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Titulo de nota</h5>
        <p class="card-text">{{text}}.</p>
        <button class="btn btn-danger float-end mx-2" href="#">Delete</button>
        <button class="btn btn-success float-end mx-2" href="#">Done</button>
      </div>
    </div>
</template>