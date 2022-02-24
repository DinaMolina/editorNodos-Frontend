<template>
 <div id="Menu">
     <div class="container">
         <div class="row align-items-center">
            <div class="col-6">
                 <div class="col-sm-auto  sticky-top">
                <div class="d-flex flex-sm-column flex-row flex-nowrap bg-light align-items-center sticky-top">
                    <ul class="nav nav-pills nav-flush flex-sm-column flex-row flex-nowrap mb-auto mx-auto text-center align-items-center">
                         <li class="nav-item">
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home">
                            <img src="https://img.icons8.com/external-vitaliy-gorbachev-lineal-vitaly-gorbachev/60/26e07f/external-numbers-support-vitaliy-gorbachev-lineal-vitaly-gorbachev.png"/>
                            </a>
                            Number
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home">
                            <img src="https://img.icons8.com/external-prettycons-solid-prettycons/60/26e07f/external-text-text-formatting-prettycons-solid-prettycons.png"/>
                            </a>
                            String
                        </li>
                           <li>
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Products">
                                <img src="https://img.icons8.com/external-outline-juicy-fish/60/26e07f/external-if-coding-and-development-outline-outline-juicy-fish.png"/>
                            </a>
                            If-Else
                        </li>
                        <li>
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Customers">
                                <img src="https://img.icons8.com/pastel-glyph/64/26e07f/loop.png"/>
                            </a>
                            For Loop
                        </li>
                      
                      
                    </ul>
                 </div>
                </div>
            </div>
            <div class="col-6">
            <div class="col-sm-auto  sticky-top">
                <div class="d-flex flex-sm-column flex-row flex-nowrap bg-light align-items-center sticky-top">
                    <ul class="nav nav-pills nav-flush flex-sm-column flex-row flex-nowrap mb-auto mx-auto text-center align-items-center">
                          <li class="nav-item">
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home">
                              <img src="https://img.icons8.com/external-flatart-icons-outline-flatarticons/64/26e07f/external-add-basic-ui-elements-flatart-icons-outline-flatarticons.png"/>
                            </a>
                            Add
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home">
                              <img src="https://img.icons8.com/external-tal-revivo-regular-tal-revivo/48/26e07f/external-minus-subtraction-symbol-in-math-isolated-on-white-background-basic-regular-tal-revivo.png"/>
                            </a>
                            Subtract
                        </li>
                        <li>
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Dashboard">
                               <img src="https://img.icons8.com/wired/64/26e07f/multiply.png"/>
                            </a>
                            Multiply
                        </li>
                        <li>
                            <a href="#" class="nav-link py-3 px-2" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Orders">
                                <img src="https://img.icons8.com/dotty/80/26e07f/divide.png"/>
                            </a>
                            Divide
                        </li>
                       
                    </ul>
                 </div>
                </div>
             </div>
         
         </div>
     </div>
       
 </div>
</template>

<script >
import { defineComponent } from 'vue';



export default defineComponent({
  name: 'Menu',
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
