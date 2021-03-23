<template>
      <div>
          <div class="titlediv">
            <div>Dashboard</div>
          </div>
          
          <div class="firstdiv">
              <img src="views/first.png"/>
              <div id="p1">255</div>
              <div id="p2">Task Complated</div>
          </div>
      
          <div class="seconddiv">
            <img src="views/second.png"/>
            <div id="p3">45</div>
            <div id="p4">Upcoming Task</div>
          </div>
      
          <div class="thirddiv">
              <img src="views/third.png"/>
              <div id="p5">82</div>
              <div id="p6">Hours Logged</div>
          </div>
      
          <div class="fourthdiv">
              <img src="views/fourth.png"/>
              <div id="p7">120</div>
              <div id="p8">Files Uploaded</div>
          </div>
        </div>
</template>

<script>

</script>

<style lang="scss" scoped>
  @font-face {
      font-family: "Lato";
      src:url("views/Lato-Regular.ttf")format("truetype")
  }

  .titlediv{
      position: absolute;
      width: 88px;
      height: 22px;
      left: 119px;
      top: 38px;

      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 18px;
      line-height: 22px;
      display: flex;
      align-items: flex-end;
      color: #333333;
  }
  .firstdiv {
      position: absolute;
      width: 210px;
      height: 110px;
      left: 119px;
      top: 96px;
      text-align: center;
      background: #E3FFE1;
      border-radius: 5px;
    }
  .seconddiv {
      position: absolute;
      width: 210px;
      height: 110px;
      left: 346px;
      top: 96px;
      text-align: center;
      background: #E1F6FF;
      border-radius: 5px;
  }
  .thirddiv {
      position: absolute;
      width: 210px;
      height: 110px;
      left: 119px;
      top: 226px;
      text-align: center;
      background: #FFF8E1;
      border-radius: 5px;
  }
  .fourthdiv {
      position: absolute;
      width: 210px;
      height: 110px;
      left: 346px;
      top: 226px;
      text-align: center;
      background: #F3F3FF;
      border-radius: 5px;
  }
  #p1 {
      position: absolute;
      width: 56px;
      height: 38px;
      left: 77px;
      top: 24px;

      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 32px;
      line-height: 38px;
      display: flex;
      align-items: flex-end;

      color: #7ADC2C;
  }
  #p2 {
      position: absolute;
      width: 98px;
      height: 17px;
      left: 56px;
      top: 75px;

      font-family: Lato;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;

      display: flex;
      align-items: flex-end;
      text-align: center;

      color: #333333;

      mix-blend-mode: normal;
      opacity: 0.5;
  }
  #p3 {
      position: absolute;
      width: 38px;
      height: 38px;
      left: 86px;
      top: 24px;
      
      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 32px;
      line-height: 38px;
      display: flex;
      align-items: flex-end;
      
      color: #328FF1;    
  }
  #p4 {
      position: absolute;
      width: 93px;
      height: 17px;
      left: 59px;
      top: 75px;
      
      font-family: Lato;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;
      
      display: flex;
      align-items: flex-end;
      text-align: center;
      
      color: #333333;
      
      mix-blend-mode: normal;
      opacity: 0.5;    
  }
  #p5 {
      position: absolute;
      width: 38px;
      height: 38px;
      left: 86px;
      top: 24px;
      
      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 32px;
      line-height: 38px;
      display: flex;
      align-items: flex-end;
      
      color: #DC932C;    
  }
  #p6 {
      position: absolute;
      width: 86px;
      height: 17px;
      left: 62px;
      top: 75px;
      
      font-family: Lato;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;
      display: flex;
      align-items: flex-end;
      text-align: center;
      color: #333333;
      opacity: 0.5;    
  }
  #p7 {
      position: absolute;
      width: 56px;
      height: 38px;
      left: 77px;
      top: 24px;
      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 32px;
      line-height: 38px;
      display: flex;
      align-items: flex-end;
      color: #8232F1;    
  }
  #p8 {
      position: absolute;
      width: 91px;
      height: 17px;
      left: 60px;
      top: 75px;
      font-family: Lato;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;
      display: flex;
      align-items: flex-end;
      text-align: center;
      color: #333333; 
      opacity: 0.5;   
  }
</style>
