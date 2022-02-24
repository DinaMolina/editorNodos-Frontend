<template>
 <div id="NodeClick">
    <div class="card-devices" >
     <div class="header">
        <h1> Test </h1>
     </div>
    <div class="body" >
       <span @click="Clicked"> Name :</span>
     </div>
  </div>
 </div>
</template>

<script >
import { defineComponent } from 'vue';



export default defineComponent({
  name: 'NodeClick',
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

</style>
