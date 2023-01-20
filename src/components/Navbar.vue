<template>

    <div class="navigation">

        <nav class="nav">
      
         <img src="../assets/logos/WeMAST.png" alt="" class="wemast_logo">

        <div class="wemast_title">
            <p>WETLAND MONITORING AND ASSESSMENT SERVICE FOR TRANSBOUNDARY BASINS IN
                <br>
                SOUTHERN AFRICA (WeMAST)</p>
        </div>

        <div class="patners">
            <img src="../assets/logos/SASSCAL.png" alt="" class="WeMast_Dashboard_logos">
            <img src="../assets/logos/Gmes.png" alt="" class="WeMast_Dashboard_logos">
            <img src="../assets/logos/Au.png" alt="" class="WeMast_Dashboard_logos">
            <img src="../assets/logos/EU.png" alt="" class="WeMast_Dashboard_logos">
        </div>

        <div class="languages">

        </div> 
    </nav>
    


    </div>
    
</template>



<script setup>
</script>



<style scoped>
.navigation{
    margin-top: 0;
    background-color: rgb(255, 255, 255);
}
.nav{
   
    width: 100%;
    height: 10vh;

 
}

.wemast_logo {
  height: 50px;
  margin-left: 5vw;
  margin-right: 35px;
  margin-top: 4vh;
}
.wemast_title {
  margin-top: -7vh !important;
  position: relative;
  left: 15vw;
  text-transform: uppercase;
}
/* @media screen and (min-width: 1440px) {
  .wemast_title {
    margin-top: 40px;
    font-size: 20px;
  }
} */
.patners{
  position: absolute;
  top: 4vh;
  z-index: 1000;
  left: 58vw;
  
}

.WeMast_Dashboard_logos {
 
    height: 45px;
   
    margin: 2px;

  }
.languages{
  position: absolute;
  top: 4vh;
  left: 90vw;
}
</style>