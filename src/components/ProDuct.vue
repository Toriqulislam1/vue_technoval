<template>
<span>{{ msg }}</span>

<div class="container">
  <div class="row">
    <div class="col-lg-4">
      <div class="card">
        <img src="@/assets/logo.png" alt="My Image" width="200px" height="200px"/>
        <div>
          <span>abc</span><br>
          <span class="">100</span><br>
          <span class="text-decoration-line-through">100</span><br>
          <a class="text-dark " href="#">add to card</a>
          <a class="float-end text-dark" href="#">Buy Now</a>
        </div>
      </div>
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: 'proDuct',
  props: {
    msg: String
  },

}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


li {
  background-color:green;
  margin-right: 10px;
  list-style: none
}
.d-flex{
  
  margin: 5px;
  display: flex;
}

</style>
