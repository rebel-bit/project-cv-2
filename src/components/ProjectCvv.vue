<template>
       <div id="section" style="text-align:justify;">
           <nav>
               <div id="name">
                   <img class="rounded-image" src="https://i.ibb.co/zZDKD09/73438bfd-d335-4f55-893e-07eacb3196b6.jpg" widt="200px" height="200px">
               </div>

               <h4 id="li">PROFILE<hr style="border:1px dashed black"></h4>

               <h4 id="li">Adrres:</h4>
               <h5 id="li">5051 semrang jawatengah indonesia</h5>

               <h4 id="li">Phone:</h4>
               <h5 id="li">+6289616061529</h5>

               <h4 id="li">Email:</h4>
               <h5 id="li">xcodetam6@gmail.com</h5>
               <br>

               <h4 id="li">langues<hr></h4>
               <h5 id="li">bhs  jawa<br>indonesia<br>inggris</h5>
            
           </nav>
       <div id="content">
    <h3>FAZA AKBAR</h3><br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

       <h3>GRAPICH ARTIST<hr style="border:1px soli black;"></h3>
      <div class="ab">
         <h3> WORK EXPREINCE<hr style="border:1px dashed black"></h3>
       <h4>CREATIVE ROOMS</h4>
       <p>feb 2013 jun2014</p><br>

       <h4>CREATIVE ROOMS</h4>
       <p>feb 2013 jun2014</p>


       <h4></h4>
    
      </div>

      <div class="ab">
          <h3>EDUCATION<hr style="border:1px dashed black"></h3>
          <h4>MASTER DEGRE</h4>  
           <p>feb 2013 jun2014</p>
      </div>
       </div>
       </div>
</template>
<script>
export default {
          name: 'ProjectCvv',
          computed:{
            listAgenda() {
              return this.$store.state.listAgenda
            }
          }
    };
</script>