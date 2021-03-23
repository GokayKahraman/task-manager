<template>
      <div style="margin-left: 39px; margin-top: 38px;">
          <div class="titlediv">
            <div>Dashboard</div>
          </div>
          <div style="margin-top: 36px;">
            <div style="display: flex;">  
                <div class="box">
                    <div class="count green">255</div>
                    <div class="title">Task Complated</div>
                </div>
            
                <div class="box" style="margin-left: 17px;">
                    <div class="count blue">45</div>
                    <div class="title">Upcoming Task</div>
                </div>
            </div>

            <div style="display: flex; margin-top: 20px;">
                <div class="box">
                    <div class="count orange">82</div>
                    <div class="title">Hours Logged</div>
                </div>
            
                <div class="box" style="margin-left: 17px;">
                    <div class="count purple">120</div>
                    <div class="title">Files Uploaded</div>
                </div>
            </div>
          </div>
        </div>
</template>

<script>

</script>

<style lang="scss" scoped>
  @font-face {
      font-family: "Lato";
      src:url("./assets/Lato-Regular.ttf")format("truetype")
  }

  .titlediv{
      height: 22px;

      font-family: Lato;
      font-style: normal;
      font-weight: bold;
      font-size: 18px;
      line-height: 22px;
      color: #333333;
  }
.box {
      width: 210px;
      height: 110px;
      text-align: center;
      background: #E3FFE1;
      border-radius: 5px;
      background-image: url("./assets/first.png");

    .count {
        font-family: Lato;
        font-style: normal;
        font-weight: bold;
        font-size: 32px;
        margin-top: 24px;
    }
}

  .green{
      color: #7ADC2C;
  }
    .blue{
      color: #328FF1;
  }
    .orange{
      color: #DC932C;
  }
    .purple{
      color: #8232F1;
  }

  .title {
      height: 17px;

      margin-top: 13px;
      font-family: Lato;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;

      text-align: center;

      color: #333333;

      mix-blend-mode: normal;
      opacity: 0.5;
  }
</style>
