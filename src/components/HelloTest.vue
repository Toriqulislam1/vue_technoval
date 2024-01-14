<template>
 <div class="d-flex">
  <li>Home</li>
  <li>About</li>
  <li>Contact</li>
  <li>Service</li>
  <li>Blog</li>
  <li>Product</li>
 </div>
   
   
 <div class="card">
  <span class="bg-info">hellow</span>

 </div> 

</template>

<script>
export default {
  name: 'HelleTest',
  props: {
    msg: String
  }
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
