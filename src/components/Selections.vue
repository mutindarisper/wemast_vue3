<template>
    <div class="selections">
        <div class="dashboard_selections">
            <label id="select_region"  class="text-weight-bold">Select region</label>

            <select name="" id=""   style="width: 150px; height:35px; position: absolute; left: 2vw; top: 3.5vh; border-radius: 20px; border: 1px  #ccc solid;">
                <option value=""></option>
            </select>

            <label id="select_indicator"  >Select Indicator</label>
            <select name="" id=""  style="width: 150px; position: absolute;
  left: 11vw; top: 3.5vh; border-radius: 20px; border: 1px  #ccc solid; height:35px;">
                <option value=""></option>
            </select>


            <label  id="select_sub_indicator">Select Sub-Indicator</label>
            <select name="" id="" style="width: 180px;position: absolute;
  left: 20vw; top: 3.5vh; border-radius: 20px; border: 1px  #ccc solid; height:35px;">
                <option value=""></option>
            </select>

            <label  id="select_year">Select Year</label>
            <select name="" id="" style="width: 150px; position: absolute;
  left: 30vw; top: 3.5vh; border-radius: 20px; border: 1px  #ccc solid; height:35px;">
                <option value=""></option>
            </select>

            <button class="request" style="">REQUEST</button>
           
        
        </div>

    </div>
</template>


<script setup>
</script>

<style scoped>
.selections{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bolder;
    font-size: 16px;
}
.dashboard_selections{
    background-color: #f6f6f6;
         position: absolute; width: 93vw;
          height: 50px; padding: 15px; top: 12vh; left: 5vw;
           border-radius: 35px; padding-bottom: 20px;
}
#select_region{
  font-weight: 600;
  font-size: 12px;
  position: relative;
  left: 1.5vw;
  top: -0.2vh;
}

#select_indicator{
  font-weight: 600;
  font-size: 12px;
  position: relative;
  left: 7vw;
  top: -0.2vh;

}
#select_sub_indicator{
  font-weight: 600;
  font-size: 12px;
  position: relative;
  left: 12vw;
  top: -0.2vh;

}
#select_year{
  font-weight: 600;
  font-size: 12px;
  position: relative;
  left: 16.5vw;
  top: -0.2vh;

}
.request{
    height: 35px;
     margin-top: 0px; 
     position:absolute; 
     outline: none; border: none; 
     border-radius: 30px; 
     left: 39vw; width: 7vw;
      top:3.5vh; color: #fff; 
      background-color: steelblue;
}

</style>