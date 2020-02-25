<style>
.card32{
  
  position: absolute;
  margin-left: 100px;
  margin-top: 100px;
  width: 300px;
    height: 500px;
}

.card33{
  
  position: absolute;
  margin-left: 450px;
  margin-top: 100px;
  width: 400px;
    height: 500px;
}

.card34{
  
  position: absolute;
  margin-left: 840px;
  margin-top: 100px;
  width: 400px;
    height: 500px;
}

.section3{
  
  position: relative;
  margin-left: 0px;
  margin-top: 100px;
  width: 513px;
    height: 500px;
}
</style>
<template>
    <section class="section3 pb-0 section-components">
        <div class="container mb-5">
            <!-- Inputs -->
           
           
            <div class="card32">
                <p class="h6 mb-0">"01  ........  ABOUT US"</p>
                <h5 class="h1 mb-0">Simple and handy rental process</h5>
                
                            </div>


                            <div class="card33">
               
                <div class="card-body">
                    <p class="h6 mb-0" style="text-align: justify;">Snow chains, surf board rack, key lock box, or dog car seat hammock available upon request.</p>
                    
                    <hr align="center" width="50%" color="black" size="3">
<blockquote class="blockquote text-white mb-0">
              
               <div class="icon icon-xs icon-shape bg-white shadow rounded-circle">
                        <i class="fas fa-hdd"></i><pre> X</pre>
                        
                      </div>
                      
                       <div id="samr21">
                           <p>interested in our values?</p>
   
</div> 
                       <p id="samr31">Learn more about the company →</p>
                       </blockquote></div>
                            </div>



                            <div class="card34">
               
                <div class="card-body">
                    <p class="h6 mb-0" style="text-align: justify;">Still got questions? We've probably covered them all in the HelpCenter.</p>
                      <hr align="center" width="50%" color="black" size="3">
<blockquote class="blockquote text-white mb-0">
              
               <div class="icon icon-xs icon-shape bg-white shadow rounded-circle">
                        <i class="fas fa-hdd"></i><pre> X</pre>
                        
                      </div>
                      
                       <div id="samr21">
                           <p>interested in our values?</p>
   
</div> 
                       <p id="samr31">Learn more about the company →</p>
                       </blockquote></div>
                            </div>



        </div>
        
            
        
    </section>

    
</template>
<script>
import BaseNav from "@/components/BaseNav";
import CloseButton from "@/components/CloseButton";
import Menu1 from "./Navigation/Menu1";
import Menu2 from "./Navigation/Menu2";
import Menu3 from "./Navigation/Menu3";
import Menu4 from "./Navigation/Menu4";
import Menu5 from "./Navigation/Menu5";
import Menu6 from "./Navigation/Menu6";

export default {
  components: {
    BaseNav,
    CloseButton,
    Menu1,
    Menu2,
    Menu3,
    Menu4,
    Menu5,
    Menu6
  },
  data() {
    return {
      menus: [
        { type: "default", menuComponent: Menu1 },
        { type: "primary", menuComponent: Menu2 },
        { type: "success", menuComponent: Menu3 },
        { type: "danger", menuComponent: Menu4 },
        { type: "warning", menuComponent: Menu5 },
        { type: "info", menuComponent: Menu6 }
      ]
    };
  }
};
</script>
<style>
</style>
