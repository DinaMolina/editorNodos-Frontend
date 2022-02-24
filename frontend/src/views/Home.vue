<template>
  <div class="home">
    <Navbar></Navbar>
    <div class="container-fluid">
      <div class="row">
        <div class="col-3 bg-light">
          <Menu></Menu>
        </div>
        <div class="col-9">
            <div id="drawflow"></div></div>
        </div>
      </div>
    </div>
  
</template>

<script>
import { defineComponent } from 'vue';
import Vue from 'vue'
import NodeClick from '@/components/NodeClick.vue'; // @ is an alias to /src
import Menu from '@/components/Menu.vue'
import Navbar from '@/components/Navbar.vue'
import Drawflow from 'drawflow'
//import styleDrawflow from 'drawflow/dist/drawflow.min.css'

export default defineComponent({
  name: 'Home',
   data() {
    return {
      editor: null,
    }
  },
  components:{
    Menu, 
    Navbar
  },
  mounted() {
    const id = document.getElementById("drawflow");
    this.editor = new Drawflow(id, Vue);
    this.editor.start();
    const props = {};
    const options = {};
    this.editor.registerNode('NodeClick', NodeClick, props, options);
    const data = {};
    this.editor.addNode('Name', 0, 1, 150, 300, 'Class', data, 'NodeClick', 'vue');

  },
});
</script>


<style>
#drawflow {
  width: 100%;
  height: 550px;
  border: 1px solid #26E07F;
}
</style>
