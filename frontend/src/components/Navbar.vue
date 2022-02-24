<template>
 <div id="Navbar">
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand title" href="#">Nodes Editor</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse my-2 my-lg-0 form-inline" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
    </ul>
  </div>
  <div class="form-inline">
    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Safe</button>
  </div>
</nav>
 </div>
</template>

<script >
import { defineComponent } from 'vue';



export default defineComponent({
  name: 'Navbar',
  props: {
    msg: String,
  },
   methods: {
    Clicked() {
      alert("hello-drawflow");
    }
  }
 
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.title{
  color: #25ac66 !important;
  font-weight: bold;
}
</style>
