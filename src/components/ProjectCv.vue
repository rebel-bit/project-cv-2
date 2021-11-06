<template>
       <div id="section">
           <nav>
               <div id="name">
                   <h1>faza akbar<br>maulana</h1>
                   <img src="https://i.ibb.co/zZDKD09/73438bfd-d335-4f55-893e-07eacb3196b6.jpg" widt="200px" height="200px">
               </div>

               <h4>contact<hr></h4>

               <h4>Adrres:<br>5051 semarang jawatengah, indonesia</h4>

               <h4>Phone:<br>+6289616061529</h4>

               <h4>Email:<br>xcodetam6@gmail.com</h4>
               <br>

               <h4>langues<hr></h4>
               <h5>bhs  jawa<br>indonesia<br>inggris</h5>
            
           </nav>
       <div class="content">
    <h3>OBJEKTIF<hr></h3>
    <h5>Penyedia analaylistick data mendukung untuk mengelola data penyedia analisis<br>mendukung penyedia</h5><br>
    
    <h3>PENGALAMAN<hr></h3>
    <h3 id="m1">04/2014 - 04/018</h3>
    <h5>Melakuakn pentesting Website  <br>Teman
       <ul>
          <li v-for="row in listAgenda" :key="row">
          {{ row.hobi }}</li>
       </ul>
       </h5>
       
    <h3 id="m2">03/2012 - 05/2014</h3>
    <h5>Melakuakn pentesting Aplikasi orang<br>
       <ul>
           <li v-for="row in listAgenda" :key="row">
          {{ row.hobi }}</li>
       </ul>
       </h5>
    
    <h3>PENDIDIKAN<hr></h3>
    <h3 id="m4">2004 - 2008</h3>
    <b>mahasiswa teknik ilmu komputer sekolah binusa smg</b>

    <h3 id="m4">2002 - 2004</h3>
    <p>mahasiswa teknik ilmu komputer sekolah binusa smg</p>
    
   <h3 id="m4">2004 - 2008</h3>
   <p>mahasiswa teknik ilmu komputer sekolah binusa smg</p>
       
   <h3 id="m4">2002 - 2004</h3>
   <p>mahasiswa teknik ilmu komputer sekolah binusa smg</p>
               
       

    <h3>KEMAMPUAN TAMBAHAN</h3>
    <h5>pengoprasian data base: Microsoft<br>Operasi statistik: STATA<br>pemrograman: php, mysql, html<br>pemrograman: php, mysql, python</h5>

    <h3>REFRENSI<hr></h3>
       refrensi permintaan yang tersedia
       </div>
       </div>
</template>
<script>
export default {
          name: 'ProjectCv',
          computed:{
            listAgenda() {
              return this.$store.state.listAgenda
            }
          }
    };
</script>